using UnityEngine; 
 
public class GitHub : MonoBehaviour 
{ 
    void Start() 
    { 
       
        while (true) 
        { 
            int RandomNumber = Random.Range(1, 21); 
            if (RandomNumber == 5);
            { 
                Debug.Log("You got a 5"); 
                continue; 
            } 
            else if RandomNumber == 15); 
            { 
                Debug.Log("You got a 15"); 
                break; 
            } 
 
            Debug.Log(RandomNumber); 
        } 
 
       
        string[] words = { "Cat", "Dog", "Car", "Pizza", "Hat", "Fish", "Tree", "Monkey", "Ball", "Bird" }; 
        System.Random random = new System.Random(); 
        string funnySentence = ""; 
 
        int wordsCount = 7; 
        int count = 0; 
 
        while (count < wordsCount) 
        { 
            int index = random.Next(0, words.Length);  
            funnySentence += words[index] + " ";       
            count++; 
        } 
 
        Debug.Log(funnySentence); 
    } 
}

