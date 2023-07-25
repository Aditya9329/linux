# linux
linux system


# 3 types of roles
-> owners/users (u)
-> groups (g)
-> others (o)

# 3 types of permissions
-> read - (r)
-> write - (w)
-> execute - (x)

# rw- r-- r--

rw- - first three represents the owner of the file
r-- - represents group permissions
r-- - represents others permissions


project - T
 module1      module2    module3
  A,B,C        D,E,F      G,H,I


# A created a file sample.txt
# owner  - who created sample.txt
# group  - (person working in the same module)
# other  - (person who are working others modules)







# 2 ways to use chmod commmand
1.symbolic/text method
2.numeric method


# create a file sample.txt and add permission called execute to the owner
chmod u+x sample.txt

write a command to add a execute permission to owner and add read writepermission to group and others
uu ---x
o  ---rw

# chmod u+x,g+rw,o+rw sample.txt




# write a command remove read permission from group  and others

g-r,o-r
chmod g-r,o-r



