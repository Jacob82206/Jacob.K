
/**
 * The program will allow the user to play a adventer type game
 *
 * @author (your name)
 * @version (a version number or a date)
 */
import java.util.Scanner;
import java.util.Random;
public class adventure_game
{
    public static void main (String[] args)
    {
        System.out.println("\u000C");
        String answer;
        
        
        Scanner input = new Scanner(System.in);
        Scanner keyboard1 = new Scanner(System.in);
     //Start of the reset while loop   
     do {
        System.out.println(" The Dragons Den ");
        System.out.println("__________________");
        System.out.println("   Press Enter    ");
        String enter = input.nextLine();
        System.out.println();
        
        
        System.out.println("This is an adventure based game if you die the game resets");
        System.out.println();
        //Create a character
        System.out.println("Create Your Character");
        System.out.println("_____________________");
        System.out.println();
        
        System.out.println("Would you like to be a male or Female?");
        String race1 = input.nextLine();
        System.out.println();

        System.out.println("Lastly what do want your name to be?");
        String name1 = input.nextLine();
        System.out.println();
        
        System.out.println("Press Enter To Continue");
        String enter2 = input.nextLine();
        System.out.println();
        //Setting
        System.out.println("You walk into a tavern");
        System.out.println();
        System.out.println("The owner of the tavern notices you");
        System.out.println();
        System.out.println("" + name1 + "! Has slain more monsters");
        System.out.println();
        System.out.println("than anyone of you in here!");
        System.out.println();
        System.out.println("As long as he lives monsters shall stay away from us!");
        System.out.println();
        
        System.out.println("You walk up to the owner and order an ale");
        System.out.println();
        System.out.println("A man in a black hood sits next to you");
        System.out.println();
        
        System.out.println("What Do you want to say");
        System.out.println();
        System.out.println("What business do you have here. (1)");
        System.out.println();
        System.out.println("Ask him how his day is going. (2)");
        System.out.println();
        System.out.println("Get up and move to another seat. (3)");
        
        int userChoice;
        userChoice = input.nextInt();
        //Dioalge options
        if (userChoice == 1)
        {
            System.out.println("I've come here to give you quests");
        }
        else if (userChoice == 2)
        {
            System.out.println("Its going pretty swell");
            System.out.println("and I have good news!");
            System.out.println();
            
            System.out.println("What? you ask him");
            System.out.println();
            
            System.out.println("I have jobs for you");
        }
        else if (userChoice == 3)
        {
            System.out.println("You move away");
            System.out.println();
            System.out.println("The man follows");
            System.out.println();
            System.out.println("What do you want? you say");
            System.out.println();
            System.out.println("I've heard you have a reputation for slaying monsters");
            System.out.println();
            System.out.println("I do. you say");
            System.out.println("I have these four quests for you");
            System.out.println("And I will pay highly he says");
        }
        
        System.out.println();
        System.out.println("The man in the hood pases you a scroll with a quest.");
        
        System.out.println();
        System.out.println("you unroll it");
        System.out.println("and read off the quest");
        
        System.out.println("I have discovered a cave in the mountains of Wessex");
        System.out.println("There is said to be a dragon living in their");
        System.out.println("I will pay who ever finds this dragon and kills it a fortune");
        System.out.println();
        
        System.out.println("You feel a rush of excitment flowing throught you");
        System.out.println("I will go and defeat that dragon! you say");
        System.out.println();
            
        System.out.println("I'll take on the Dragon for you! you say");
        System.out.println();
        System.out.println("I will pay half now and the rest when you return. says the hooded man");
        System.out.println();
            
        System.out.println("You get some rest that night and early in the morning");
        System.out.println("you get on your horse and ride west of the tavern");
        System.out.println();
            
        System.out.println("You look at your map to see where the Dragon's den is");
        System.out.println("When you find it, it is dark and cold");
        System.out.println("You tie up your horse on a near by tree and wak in");
        System.out.println();
            
        System.out.println("The cave sysetem spits in two");
        System.out.println("Which path woud you like to take?");
        System.out.println();
            
        System.out.println("Left (1)");
        System.out.println("Right (2)");
            
        int leftRight;
        leftRight = input.nextInt();
            
           if(leftRight == 1)
           {
                System.out.println("you walk left trying to find the den");
                System.out.println("the Dragon fly's throught the wall");
                System.out.println("You get chased out of the cave into the mud that surronds you");
                System.out.println("The creature uses the cover of night to hide itself before it attacks!");
                System.out.println();
                
              
                // start of the attack phase
                    int dragHealth = 300;
                    int damage = 15;
                    
                    Random rand = new Random();
                    int RandomDD = rand.nextInt(20) + damage; 
                    dragHealth -= RandomDD;
                   
                    System.out.println("You try to attack it");
                    System.out.println();
                    
                    System.out.println("You swing your sword and get a hit on the Dragon for " + RandomDD + " damage. The");
                    System.out.println("dragon's heath is now at " + dragHealth + "");
                    System.out.println();
                    
                    System.out.println("The Dragon goes back into the darkness hiding from you");
                    System.out.println("It leaps out at you but you parry the attack");
                    System.out.println();
                   
                    System.out.println("It's vulnerable! Where do you attack!?");
                    System.out.println();
                    
                    System.out.println("Neck (1)");
                    System.out.println("Stomach (2)");
                    
                    int attack3;
                    attack3 = input.nextInt();
                    
                if (attack3 == 1)
                {
                        System.out.println("You go for the neck");
                        System.out.println("You do " + RandomDD + " damage");
                        System.out.println("The dragon has " + dragHealth + " health");
                        System.out.println();
                        
                        System.out.println("The dragon is vulnrabe!");
                        System.out.println("You charge you charge it putting your sword up it's neck,");
                        System.out.println("killing it!");
                        System.out.println("You take the skull back to the hooden man and take your reward");
                }
                if (attack3 == 2)
                {
                    System.out.println("you go for the stomach but the dragon recovers wacking");
                    System.out.println("with its tail sending you flying");
                    System.out.println("You think to yourself, Thats it the mighty " + name1 + "");
                    System.out.println("defeated");
                    System.out.println("You hit a tree with har force killing you");
                }
                
                
                
        
            }     
                
            if (leftRight == 2)
            {
               System.out.println("You take the right path");
               System.out.println("Your torch gives light to the cave walls around you");
               System.out.println("You hear snoring. When you cross a corner you feel a sence of terror");
               System.out.println("The dragon is sleeping");
               System.out.println();
               
               System.out.println("What do you want to do?");
               System.out.println();
               
               System.out.println("Attack (1)");
               System.out.println("Sneak Attack (2)");
               
               int playerAttack;
               playerAttack = input.nextInt();
               if (playerAttack == 1)
              {
                   int dragHealth = 300;
                   int damage = 15;
                    
                   Random rand = new Random();
                   int RandomDD = rand.nextInt(20) + damage; 
                   dragHealth -= RandomDD;
                  
                   
                   System.out.println("You attack!");
                   System.out.println("You strike the dragon with your sword");
                   System.out.println("You do " + RandomDD + " Damage. The Dragons health is at " + dragHealth + "!");
                   System.out.println();
                   
                   System.out.println("The dragon retreats out of its cave and shoots through the sky!");
                   System.out.println("You grab your horse and follow after it");
                   System.out.println("The dragon lands in a field");
                   System.out.println("Your horse stops out of fear and knocks you off");
                   System.out.println("The Dragon begins to charge up an attack!");
                   System.out.println();
                   
                   System.out.println("What do you do?");
                   System.out.println();
                   
                   System.out.println("Try to dodge the attack (1)");
                   System.out.println("Try to charge the Dragon (2)");
                   
                   int action2;
                   action2 = input.nextInt();
                   
                   if (action2 == 1)
                  {
                    int playHealth = 100;
                 
                    int RandownWDD = rand.nextInt(30) + damage;
                    playHealth -= RandomDD;
                       
                       
                       
                    System.out.println("You try to dodge the attack from the dragon");
                    System.out.println("But you get hit!");
                    System.out.println("You took " + RandomDD + " and your health is at " + playHealth + "!");  
                   
                  }
                  if (action2 == 2)
                  {
                    int playHealth = 100;
                 
                    int RandomWDD = rand.nextInt(30) + damage;
                    playHealth -= RandomWDD;
                      
                    System.out.println("You try to charge the dragon but it slaps you with its tail knocking your sword away!");
                    System.out.println("The Dragon does " + RandomWDD + " to you and your health is now at " + playHealth + "!");
                    System.out.println("Luckily your sword stabs the Dragon on it's side!"); 
                    System.out.println("The Dragon took " + RandomWDD + " and it's health is now " + dragHealth + "!");
                    System.out.println("You run to retrieve your sword while the dragon is stunned");
               
                  }      
                  
                  System.out.println("With your sword in hand you charge up your final attack");
                  System.out.println();
                  
                  System.out.println("Do you want to attack now or keep charging?");
                  System.out.println();
                  
                  System.out.println("Wait (1)");
                  System.out.println("Attack (2)");
                  
                  int choice;
                  choice = input.nextInt();
                  if (choice == 1)
                  {
                     
                      
                      System.out.println("you wait for the dragon to attack!");
                      System.out.println("When it charges you jump up just as it bites at you");
                      System.out.println("You stab it's head killing it");
                      System.out.println();
                      
                      System.out.println("You travel back to the tavern and give the head of the dragon to the man in the hood");
                      System.out.println("Thank you " + name1 + ", you have pleased me");
                      System.out.println("you give him  a nod and with that you have Completed your quest!"); 
                     
                  }
                  if (choice == 2)
                  {
                      System.out.println("You decide to attack");
                      System.out.println("You try to leep into the Dragon but it gets the upper hand and bites your leg!");
                      System.out.println("You try to free yourself but its to late");
                      System.out.println("You slowly slide into the dragons throat and then... Darkness");
                  }
               }    
                  
            
                if (playerAttack == 2)
               {
                   int dragHealth = 300;
                    int damage = 15;
                    
                    Random rand = new Random();
                    int RandomDD = rand.nextInt(20) + damage; 
                    dragHealth -= RandomDD;
                    
                   System.out.println("You try to sneak up on the dragon");
                   System.out.println("You stab the dragon doing " + RandomDD + " damage to it. It's health is at " + dragHealth + "");
                   System.out.println();
                     
                   System.out.println("The Dragon wakes up and freaks out causing a cave in");
                   System.out.println("You get trapped inside");
                   
                   System.out.println("You wake up in shock to find nothing but darkness");
                   System.out.println("You try to move but are not able to");
                   System.out.println();
                
                   System.out.println("A day passes");
                   System.out.println("I " + name1 + " really was beaten by cave in!");
                   System.out.println("You scream at the top of your lungs expressing anger");
                   System.out.println("You die alone in the cave");
               }
                    
               
                
               
            }
            //code for reset
            System.out.println("Do you want to replay? Yes or No");
            answer = keyboard1.next();

        }
        while (answer.equals("Yes"));
    }
}
        
        
        
        
            
            
            
       
        
        
        
        
        
        
        
        
        
        
        
       
    







           
        
       
            
        
       
           
        
        
        
        
        
        
       
        
        
        
        
       
        
       
        
        
        
    

        
       
        
        
        
      
   
