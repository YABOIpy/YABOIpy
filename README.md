
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
        "GoLang": "30%",
        "Ruby": "10%" ,
        "JS": "5%"
     },
     "About": {
        "yaboi": "smart & retarded at the same time"
     }
   }
}
------------------------------------------

```
  
</h1>



<h2 align="center"> 
 <p align="center">   
 
<img height=170 src="https://github-readme-stats.vercel.app/api/top-langs/?username=YABOIpy&langs_count=8&theme=dark">




 <img height=170 src="https://github-readme-stats.vercel.app/api?username=YABOI-py&count_private=true&show_icons=true&theme=dark"> 
 </h2> 

 </p> 

 
