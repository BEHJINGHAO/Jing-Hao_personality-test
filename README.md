# Jing-Hao_personality-test
Please indicate your favourite option and hobby
print("Title of program: CCA Matching Personality test")
print()
print("Welcome to DHS! Please answer the following questions truthfully and we'll suggest a CCA for you!")
print("Please respond with a number 1 - 5, where 1 is strongly disagree and 5 is strongly agree.")
print()

tech1 = input("I enjoy disocvering more about electronics.")

outdoor1 = input("I do not like staying at home.")

music1 = input("Music relieves stress.")

tech2 = input("I am able to use technology for various useful means, such ascreating websites for advertising.")

outdoor2 = input("I enjoy tying knots and cooking by myself.")

music2 = input("I have learnt how to play a musical instrument before.")


tech_final = int(tech1) + int(tech2)
outdoor_final = int(outdoor1) + int(outdoor2)
music_final = int(music1)+ int(music2)

print()

if tech_final > outdoor_final and tech_final > music_final:
  print("You might be suitable for Infocomm club!")
elif outdoor_final > music_final:
  print("You might be stuiable for ODAC!")
else:
  print("You might be suitable for Band!")

  

