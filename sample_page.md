## Game Programs Tutorials

**Project description:** Basic directions on how to play games

### 1. Reaper Haunting

In Reaper Haunting, you play as a newly acquainted Grim Reaper after your successor has retired from centuries of reaping souls. Only just as the previous reaper retires, many vengeful souls take it as opportunity to leave their respective realms as you were given little to no training in your field. As the new appointed Angel of Death it is you job to reap Deviant souls and those whose time is nigh. In you journey you may also meet lost souls and those who are to be judged for banishment or reincarnation.

```javascript
 if (Inventory.Count > 0)
            {


                int index = 1;
                foreach (var item in collection)
                {
                    Console.WriteLine($"{index}) {item.Name}: {item.Description}");
                    index++;
                }

            }
            else
            {
                Console.WriteLine("Oh no... You're Inventory... It's empty");
            }

            Console.WriteLine("Smash any key to cont.");
            Console.ReadLine();
```
You must traverse to different worlds before placing each artifact in each place. To find these artifacts you must purify some deviant souls to get by.

### 2. Adopt A robot

In this game, you are simply adopting a robot and customizing it to your liking

```   

  WriteLine($"Congratulations {player.Name}! You have adopted a {player.PlayerRobot.Color} robot named {player.PlayerRobot.Name}. Press any key to exit.");
            ReadKey();
public void chooseColor(string c) 
        {
            switch (c)
            {
                case "1":
                    player.PlayerRobot.Color = "blue";
                    break;
                case "2":
                    player.PlayerRobot.Color = "purple";
                    break;
                case "3":
                    player.PlayerRobot.Color = "green";
                    break;
                case "4":
                    player.PlayerRobot.Color = "brown";
                    break;
                case "5":
                    player.PlayerRobot.Color = "black";
                    break;
                case "6":
                    player.PlayerRobot.Color = "coral";
                    break;
                default:
                    player.PlayerRobot.Color = "silver";
                    break;

```

### 3. Array

In this Assignment, you had to practice creating an array where you are able to choose items with numbered keys

```string myName = "Zacharie";

            string[] items = new string[] { "carrot", "apple", "basketball" };

            Console.WriteLine(items[0]);
            Console.WriteLine(items[1]);
            Console.WriteLine(items[2]);

            //Number array                0  1  2  3  4
            int[] myNumbers = new int[] { 1, 5, 8, 9, 5 };

```
