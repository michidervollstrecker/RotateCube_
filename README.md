# RotateCube_
using System;
using UnityEngine;

public class cylinder : MonoBehaviour
{
    // Start is called once before the first execution of Update after the MonoBehaviour is created
    void Start()
    {

    }

    // Update is called once per frame
    void Update()
    {
        Vector3 v3 = new Vector3();
        v3.y = v3.y + 1;
        v3.x = (float)(v3.x + Convert.ToDouble(0.5));
        v3.z = v3.z;
        transform.Rotate(v3.x, v3.y, v3.z);
    }
}
