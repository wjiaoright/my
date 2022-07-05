#            untiy 使用技巧

## 1.Cinemachine：第一第三人称切换

[https://github.com/yangmingxian/UnityTutorialsFiles/tree/main/Cinemachine]

## 2.碰撞检测方法

```


    /// <summary>
    /// 碰撞检测
    /// </summary>
    /// <param name="collision"></param>
    private void OnCollisionEnter(Collision collision)
    {

        if (collision.gameObject.tag == "food")
        {
            Destroy(collision.gameObject);//碰撞到的食物，销毁
        }
    }
```

