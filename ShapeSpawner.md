```C#
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class ShapeSpawner : MonoBehaviour
{

    //Variables created from our "Shape" object component
    public Shape myCube;
    

    // Start is called before the first frame update
    void Start()
    {
        /*
         * Debug.Log("Press the left arrow to hide your name " + name + " and surname " + surname + " from opponent");
         */
    }


    // Update is called once per frame
    void Update()
    {
        if (Input.GetKeyDown(KeyCode.Space))
        {
            Instantiate(myCube);
        }
    }
}
```
