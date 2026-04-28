# Ex.No-2-Welcome-Script-in-UnityDATE:
### REGISTER NUMBER : 212223240013
### NAME: ARCHANA T
## AIM:
To learn the basic scripting in Unity and print welcome message in Console window.

## Procedure:
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
## Program
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
## Output:
<img width="1912" height="992" alt="exp-2 1" src="https://github.com/user-attachments/assets/2ba5432e-f2d7-4304-bb7d-f56a13b52f93" />
<img width="1902" height="966" alt="exp-2 2" src="https://github.com/user-attachments/assets/2f087803-20de-46ee-9120-da9e1e1a73b1" />

## Result:
Thus the welcome script was printed on Console Window sucessfully.
