# CS_NOTE
note
### 指令及實作  
>1.絕對路徑：路徑的寫法『一定由根目錄 / 寫起』，ex： /usr/share/doc 這個目錄。   
>2.相對路徑：路徑的寫法『不是由 / 寫起』，ex由 /usr/share/doc 要到 /usr/share/man 底下時，寫成： 『cd ../man』    
   **相對路徑意指:相對於目前工作目錄的路徑**.  
   
    cd 變換目錄. 
    pwd 顯示目前的目錄. 
    mkdir 建立一個新目錄. 
    rmdir 刪除一個裡面是空的空目錄. 
    cp 複製. 
    mv 移動. 
    ls 顯示目錄下的所有內容. 
    cat 查看檔案內容. 
     
    nano----建立檔案  
       Ctrl C：顯示游標所在  
       Ctrl W：查詢命令，按下後會跳轉到末行的反白位置，輸入要查詢的內容在回車及可。
### 使用者與群組. 
  關於身份：  
  身份分類：  
  >1.user (owner).  
  >2.group.  
  >3.others. 
  群組 (group) 的主要用意:  
  將帳號歸類，有助於類似專案開發；每個使用者均可加入多個群組。  
  關於身份類別：  
  一般帳號：
系統帳號 (用於系統帳號的工作)
一般使用者帳號 (用於一般使用者登入用。). 

  /.(根目錄):所有的檔案皆從根目錄開始，只有root使用者具該目錄的許可權  
  /bin:存著經常使用的指令
  /boot:系統啟動時必須讀取的檔案，包括系統核心、連線檔案以及映象檔案
  /dev:存放周選設備代號的檔案  
  /etc:放置與系統設定、管理相關的檔案  
  /home:存放普通使用者的主目錄，在Linux中每個使用者都有一個自己的目錄，一般該目錄都是使用使用者的帳號命名  
  /media:可用來做為光碟、軟碟片、隨身碟與其他分割區的自動掛載點  
  /tmp:供全部使用者暫時放置檔案的目錄  
  /usr:為非常重要的目錄，使用者的很多應用程式和檔案都放在此目錄下，類似windows下的program files目錄  
  /var:系統執行時，内容經常變動的資料或暫存檔 (10g file)，都會放置在這個目錄裡
     
## 壓縮的差別 ##.  
>1.gzip.  
> 壓縮：gzip FileName.  
> 解壓縮： gunzip FileName.gz.   
> 2.xz.  
> 壓縮：xz -z FileName.   
> 解壓縮：xz -d FileName.xz.   
> 3.tar.gz. 
> 壓縮：tar -zcvf FileName.tar.gz DirName.  
> 解壓縮：tar -zxvf FileName.tar.gz.  

 
>  比較.  
>  解壓縮用時  bzip2>xz>gizp








