
```
  	                                                    YABOI
```


<details>

  <summary> <h2 align = "center">main.py</h2><h4>. Click to see code </h4></summary>
  <br>
  
  
```python
import httpx, time, os


def main(user):

    headers = {
      "content-type": "application/json"
      "auth": "aWxvdmVjdW5ueQ=="
    }
    payload = {
      "username": user
    }
    try:
        x = client.get(f"http://yaboi.com/database/{user}/info", headers=headers, json=payload)
        if x.status_code == 200:
            print(x.json)
        elif x.status_code != 200:
            print("Failed: ", x.text)
          
     except Exception as err:
         print(err)


def menu():
    global client
    db = client.get(f"http://yaboi.com/database").text.splitlines()
    user  = input("[>] Username: ")
    if user in db:
        proxy = "nl.yaboi.com:6969"
        proxies = {"http://": f"http://{proxy}"}
        client = httpx.Client(proxies=proxies)
        main(user)
    else:
        print("User: ",user, + "Not Found")
        time.sleep(1)
        os.system("cls||clear")
        menu()
menu()

```

</p>
</details>

```cmd
-----------------CONSOLE-----------------
[>] Username: YABOI
{
  "YABOI": {
     "connections": {
        "Server": "https://discord.gg/downcord"
        "Discord": "YABOI#0001",
        "Telegram": "https://t.me/yaboipy"
        },
     "Coding Langs": {
        "Python": "90%",
        "GoLang": "60%",
        "Ruby": "10%" ,
        "JS": "5%"
     },
     "About": {
        "yaboi": "ambatablouw"
     }
   }
}
------------------------------------------

```
  
</h1>



<h2 align="center"> 
 <p align="center">   


<img height=170 src="https://github-readme-stats.vercel.app/api/top-langs/?username=YABOIpy&langs_count=8&theme=onedark">




 <img height=170 src="https://github-readme-stats.vercel.app/api?username=YABOI-py&count_private=true&show_icons=true&theme=onedark"> 
 <img height=160 src="https://media2.giphy.com/media/LMt9638dO8dftAjtco/giphy.gif">
 <img height=170 src="https://camo.githubusercontent.com/82a5f91b3c5f8ff699f9a79ef46a81b3c7800d7e8e63651b1a75810f24106b0e/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f656d6f6a69732f3739353534343133343431363732383036352e676966">
 </h2> 

 </p> 

 
