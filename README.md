# MSS04-labs
# opening/creating and writing a tect file
f=open("test.txt","w+")
f.write("this is a test")
f.close()
# reading from a text file
f=open("test.txt","r")
data=f.read()
print(data)
