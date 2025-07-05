
# 🗳️ Voter Registration Form (Java)

A simple console app to register voters without a database—using in-memory storage (with optional file I/O).

## Features
- Register new voters (name, ID, DOB, address)  
- View all registered voters  
- Search by voter ID  
- Optional: save/load data to CSV/JSON

## Setup & Run
```bash
git clone https://github.com/purvaa-12/voter-registration-java.git
cd voter-registration-java
# (If Maven is used)
mvn clean package
java -jar target/voter-registration-1.0.jar
