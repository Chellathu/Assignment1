# Assignment1
Used Id create and Password
name = str(input("Name: "))
surname = str(input("Surname : "))
email = str(input("Email : "))
password = str(input("Password : "))
confPassword = str(input("ConfPassword : "))
  
if(password == confPassword):
     print("User Accepted!")
     user = createUser(chellathurai, M, chellathurai619@gmail.com, Chella@4964)
  else:
     print("User Rejected! Invalid Password Combination")
