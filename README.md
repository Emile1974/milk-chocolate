# milk-chocolate
 schoolopdracht

# Do not modify these lines
__winc_id__ = '71dd124b4a6e4d268f5973db521394ee'
__human_name__ = 'strings'

# Add your code after this line


from pydoc import Helper


player_1 = 'Ruud Gullit '
player_2 = 'Marco van Basten'
player_3 = 'Erwin Koeman'
player_4 = 'Adri van Tiggelen'
player_5 = 'Emile de jong'


scorer_name0 = (player_1) #every player that scored ###1.1
scorer_name1 = (player_2) #every player that scored

goal_0 = 32 #goal in minute  ###1.2
goal_1 = 54 #goal in minute


scorers = scorer_name0 + str(goal_0) + ", "+ scorer_name1 + " "+ str(goal_1) ###1.3
print (scorers)

#print (scorers)  ###1.3
report = f"{scorer_name0}scored in the {goal_0}nd minute" '\n' f"{scorer_name1} scored in the {goal_1}th minute"  ###1.4
print (report) #all scores  ###1.4

player = (player_3)
print (player) ###2.1  player = variable

###2.2 first_name
j = player.find(' ') #answer=(space between first and last name)
first_name = (player[0:j]) #slicing
print(first_name) #erwin
#print(first_name[2:]) #win
#print(first_name[0:4]) #erwi
#print(first_name[::-1]) #niwre
#print(first_name[2::2]) #wn

###2.3 last_name_len
j = player.find(' ') #answer=(space between first and last name)
k = (len(player))
last_name_len = (len(player[j:k])-1) # length of last name answer=6 is a variable now
print (last_name_len)

###2.4 name_short
first_name1 = (player[0:1]) #slicing first letter
#print (first_name)
last_name = (player[j:k]) # length of last name answer=6 is a variable now
#print (last_name)
name_short = first_name1 + "." + last_name
print (name_short)

###2.5 chant
first_name = (player[0:j]) #slicing
#print (first_name)
first_name_len = (len(first_name[0:j])-1)
#print (first_name_len)
chant0 = ((first_name +"! ")* first_name_len)
chant1 = (first_name +"!")
chant =  chant0 + chant1
print (chant)

###2.6 good_chant
good_chant = chant != chant1
print (good_chant)