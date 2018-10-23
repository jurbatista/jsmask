# jsmask
Aplicar máscaras em values através de javascript / apply mask in values fields through javascript


function mascara(mascara, string){
    var r = mascara.split("");
    for(i = 0; i < string.length ; i++){
        r[r.indexOf("#")] = string[i] ;
    }
    return r.join(""); 
  }
