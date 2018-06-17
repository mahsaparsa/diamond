def diamond(height):
    """Return a string resembling a diamond of specified height (measured in lines).
    height must be an even integer.
    """
    h= height/2
    print(up(h)+"\n"+down(h))
    
def upslash(h):
    if h == 1:
        return("/\\")
    return "/" + upslash(h-1) + "\\"
        
    
def up(height):
    h=1
    st = (int(height-h))*" " +upslash(h)
    while(h<height):
        h = h+1
        st = st+ "\n" +(int(height-h))*" "+ upslash(h)
        
    return st

def downslash(h):
    if h == 1:
        return("\\/")
    return "\\" + downslash(h-1) + "/"
        
    
def down(height):
    h=height
    st = downslash(h)
    while(h>1):
        h = h-1
        st = st + "\n" + (int(height-h))*" " + downslash(h)
        
    return st

diamond(50)
