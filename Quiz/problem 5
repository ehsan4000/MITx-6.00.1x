def laceStrings(s1, s2):
    """
    s1 and s2 are strings.

    Returns a new str with elements of s1 and s2 interlaced,
    beginning with s1. If strings are not of same length, 
    then the extra elements should appear at the end.
    """
    # Your Code Here
    s=''    
    i=0
    while (len(s1))>i and (len(s2))>i:
        s+=s1[i]
        s+=s2[i]
        i+=1
    if len(s1)<len(s2):
        s+=s2[i:]
    elif len(s1)>len(s2):
        s+=s1[i:]
    return s
