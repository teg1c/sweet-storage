# i-storage
给localStotage整合了过期时间的功能

## 简介


## 如何使用

###  npm 下载
  ```
  npm install sweet-storage
  ```
  
  ```javascript
    import storage from 'sweet-storage'
    storage.save('name', 'storage', 3000)
    storage.on('name', (key)=> {
      console.log(key + '过期了被删除了')
    })
  ```

###  直接引入
<<<<<<< HEAD
  ```
  git clone https://github.com/Chechengyi/sweet-storage.git
=======
  ```
  git clone https://github.com/Chechengyi/sweet-storage.git
  ```
  
  ```javascript
    <script src='./storage/release/storage.js'></script>
    storage.save('name', 'storage', 3000)
    storage.on('name', (key)=>{
      console.log(key + '过期了被删除了')
    })
>>>>>>> 451dda698a879674a75a3abe39dbf633a487e9b3
  ```
  
  ```javascript
    <script src='./storage/release/storage.js'></script>
    storage.save('name', 'storage', 3000)
    storage.on('name', (key)=>{
      console.log(key + '过期了被删除了')
    })
  ```