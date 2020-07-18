import mysql.connector


mydb = mysql.connector.connect(host="localhost", user="rushil", password="rushil@2000", database="rushil")

mycursor = mydb.cursor()

mycursor.execute("select * from friends ")

result = mycursor.fetchone()
print(result)
