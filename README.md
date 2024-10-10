planet_names = ["Mercury", "Venus", "Earth", "Mars", "Jupiter", "Saturn", "Neptune", "Uranus"] 
short_names = [] 
long_names = [] 
for  pn  in planet_names: 
if len(pn)>5: 
        long_names.append(pn) 
else: 
        short_names.append(pn)
print(short_names) 
print(long_names)
