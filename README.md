# -Write-a-program-return-resolve-if-value-is-less-than-5-using-Promise

  <a href="https://www.w3schools.com/js/js_promise.asp" target="_blank">JavaScript Promises</a>
       
       
       
      function fun(a){
        let myPromise = new Promise((myResolve, myReject)=> {
        let x = 0;
                    // The producing code (this may take some time)
              if (a < 7) {
                    myResolve(`number is given ${a}`);
              } else {
                    myReject("Error");
              }
       });
          myPromise.then((result)=>{
                 console.log(result)
          })
       }
             fun(50);
   
             fun(5);
   
   
   
   
 OUTPUT : Uncaught (in promise) Error   
  
  
 OUTPUT:   number is given 5

   
   
   
   
   
   
   
