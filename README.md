# iniciar o mongoshell
sudo service mongod start

# parar o mongoshell
sudo service mongod stop

# abrir o mongoshell
mongo

# MongoDB Relations:

=> One-to-one
Embed or not? Considerations:
- frequency of access
- size of items
- atomicity of data

=> Many-to-many
- Depends on your system access requirements
- Depends on size of items

# Benefits of embedding
- Improve read performance
- One round trip to the DB