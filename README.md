# beer-on-the-wall
# its the lyrics

count=99

while count>0:
    if count >1:
        bottle = "bottles"
    else:
        bottle = "bottle"
    
    print(str(count)+" "+bottle+" of beer on the wall, " +str(count)+" "+bottle+ " of beer.")
    
    count -= 1
    
    if count >1:
        bottle = "bottles"
    elif count ==1 :
        bottle = "bottle"
    else:
        bottle = "bottle"
        count = "no more"
        

    print("Take one down and pass it around, " +str(count)+" "+bottle+ " of beer on the wall.\n")
    if count == "no more":
            print("No more bottles of beer on the wall, no more bottles of beer.\nGo to the store and buy some more, 99 bottles of beer on the wall.")
            break
    
