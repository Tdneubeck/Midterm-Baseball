# Program to calculate what the runner hit based on how far they ran
'''
{
do_calc = True
while (do_calc == True):
    while (True):
        try:
            x = int(input("how many feet did the runner run?: "))
            if (x > 360):
                print( "runner can only run up to 360 feet please enter number between 0 and 360")
            elif ( x > 0 and x < 90):
                print ( "runner got out")
            elif ( x >= 90 and x < 180):
                print("runner hit a single")
            elif ( x >= 180 and x < 270):
                print("runner hit a double")
            elif ( x >= 270 and x < 360):
                print (" runner hit a triple")
            else:
                print (" runner hit a homerun")
            break
        except():
            print("invaild input please put a number between 0 and 360")
    another_calculation = input("do you want to calculate another cylinder? (y/n):")#asks user if they would like to do another calculation 
    if(another_calculation != "y"):
        do_calc = False
        print( "Thank you for your calculations")
        }
        '''

[return to Homepage](https://github.com/Tdneubeck/Midterm-Baseball/blob/main/README.md)

