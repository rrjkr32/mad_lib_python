# mad_lib_python
An interesting word game

    lib='''
        {}.But! {} only if you be {} of valor!
        For {} is guarded by a {} so {},
        so {}, that no {} yet has {}
        with it .... and {}!
        '''
    def main():
        command= input("Enter a command (e.g., Eat):")
        plural_noun=input("Enter a plural noun(e.g., girls):")
        animal=input("Enter an animal(e.g.,dog):")
        location=input("Enter a loacation (e.g.,the playground):")
        singular_noun=input("Enter a singular noun(e.g., man):")

        adjectives=[]
        adjectives.append(input("Enter an adjective(e.g., beatiful):"))
        adjectives.append(input("Enter an another adjective(e.g., good):"))

        past_participles=[]
        past_participles.append(input("Enter a past participle (e.g., gone):"))
        past_participles.append(input("Enter another past participle (e.g., played):"))

        str=lib.format(command,command,plural_noun,location,animal,adjectives[0],adjectives[1],singular_noun,past_participles[0],past_participles[1])
        print(str)
        
    main()
