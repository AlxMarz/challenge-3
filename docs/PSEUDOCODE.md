GOAL: make a password

# step 1:
    -click a button 
        -ask a question 
            -how many characters?
                -at least 8
                -no more than 128
                - check this before moving on 
            -uppercase? (character type)
            -lowercase?  (character type)
            -special characters? (character type)
            -numbers? (character type)
        - make sure they check at least one of the 4 characters types above

step 2:
    -what needs to be in place to get here?
    -password criteria. at lease one character type from previous step and how many characters 
    -what characters are we using?
    -if uppercase what characters ? A,B,C
    -if lowercase what characters ? a,b,c
    -if i want special characters ? !,@,#
    -if i want numbers ? 1,2,3
    -need to reference these characters somewhere 


step 3:
    -generate the password.
    -get a random character from the appropriate character type based off what user wants.  
    -also guarantee that the finished password meets all criteria the user selected.
    -how do we guarantee we get a character for the required criteria  
        -SCENARIO
            -user wants a password with all the criteria.
                -Grab 1 uppercase, 1 lowercase, 1 number, 1 symbol. any other character can any character out of the available pool after that? (shuffle) 
                -build master pool of characters out of all available character types 