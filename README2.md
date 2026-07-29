# Ex.No: 2  Welcome Script in Unity
### DATE: 29-07-2026                                                                           
### REGISTER NUMBER : 212224243005
### AIM: 
 To learn the basic scripting in Unity and print welcome message in Console window. 
### Procedure:
1. Start the program
2. Open the Unity hub and Create a new 3D project
3. In Assets window, create the new folder and name it as Scripts
4. Create a new script with file name as FirstScript
5. Open the Script and print message "Welcome to Unity" inside the start function
6. Save the script
7. Create a new 3D game object in Hierarchy window and name it as 3DObject.
8. Add the component Firstscript in inspector window of 3Dobject.
9. Run the program
10. Stop the program.
### Program 
```
using System.Collections;
using System.Collections.Generic;
using UnityEngine;
public class FirstScript : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {
        print("Welcome to Unity");
    }

    // Update is called once per frame
    void Update()
    {
        
    }
}
```
### Output:
<img width="622" height="348" alt="console" src="https://github.com/user-attachments/assets/37447973-4575-4bed-8f55-1991b923ae94" />
<img width="1271" height="800" alt="main" src="https://github.com/user-attachments/assets/d957bf5d-b9f6-440e-8bcf-9707d067a541" />
<img width="1271" height="800" alt="main" src="https://github.com/user-attachments/assets/85bbca44-1ed5-446b-9c9b-338abb595291" />


### Result:
Thus the welcome script was printed on Console Window  sucessfully.
