def McNuggets(n):
    """
    n is an int

    Returns True if some integer combination of 6, 9 and 20 equals n
    Otherwise returns False.
    """
    # Your Code Here
    for a in range(int(n/6)+1):
        for b in range(int(n/10)+1):
            for c in range(int(n/20)+1):
                if (6*a+9*b+20*c)==n:
                    print('a={0} b={1} c={2}'.format(a,b,c))
                    return True
                    break
    return False
