# Ex.No: 2  Welcome Script in Unity
### DATE: 08.09.2026                                                                           
### REGISTER NUMBER : 212225040453
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
<img width="1268" height="652" alt="Screenshot 2026-09-08 144554" src="https://github.com/user-attachments/assets/a9469a20-3082-42a9-8315-01f9e1bd732f" />

<img width="1248" height="627" alt="Screenshot 2026-09-08 144537" src="https://github.com/user-attachments/assets/fb5c98cf-fee6-4384-beb5-6a5058fae6fa" />



### Result:
Thus the welcome script was printed on Console Window  sucessfully.

