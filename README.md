emport random 
def check_win(user, computer):
    if(user == and computer 's') or (user == 's' and computer == 'p') (user == 'p' and computer =='r' and computer ==  'r'):
        return true
    def rock_paper_scissors():
        player = input("what is your choice - 'r' for rock, 's' for scissor, 'p' forpaper: ")
        choices = ['r','s','p']
        opponent = random.chice(choices)
        
        if player == opponent:
            return print(f"its a tie! choice is {opponent}")
        
        if check_win(player, opponent):
            return print ("Yay! you won! choice is {opponent}")
        
        if check-win(player, opponent) != true:
            return print(f"you lost! choice is {opponent}") 
rock_paper_scissors()
