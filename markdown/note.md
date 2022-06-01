# Notes on Client Server Model

### 1. Difference between HTTP and HTTPs.

a. HTTP lacks security to encrypt the data being transmitted, whereas HTTPs provides a certain type of
certificate known as TLS or SSL that helps to secure the communication between the client and the server

b. HTTP operates on port 80 and HTTPs operates on port 443.

c. In HTTP, data is transmitted without any encryption but in HTTPs data transmitted is encrypted.

### 2. Thick Client and Thin Client

#### Thick Client

A thick client is a type of client which can run itself regardless of the resources provided by the server.
It necessarily doesn't need the resources provided by the server and can run itself, however it does need to connect to the server to communicate and exchange information with it. It's also called a "fat client".

Example of Thick Client: Computer

### Thin Client

On the other hand, a thin client is a type of client which is heavily dependent on the resources provided by the server. It always relies on the server to do smalles of things for its own.

Example of Thin Client: Web Browser

# Tools Required Java Development

1. JDK(Java Development Kit) => >=v17.0<18
2. Apache NetBeans(IDE) => v13
3. XAMPP
4. TomCat
