# net-webapi
 //EF连接mysql https://blog.csdn.net/shujudeliu/article/details/80846894
 
   Install-Package EntityFramework -Version 6.0.0
   
   Install-Package MySql.Data -Version 6.9.8
   
   Install-Package MySql.Data.Entity -Version 6.9.8
   
   LocalDataStoreSlot slot = Thread.AllocateNamedDataSlot("slot");
  
   Thread.SetData(slot, "hehe");
            
   var obj= Thread.GetData(slot);
