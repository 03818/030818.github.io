function f(a,b){
    if(a>b){
        return "a>b";
    }
    else if(a<b){
        return "a<b";
    }
    else if(a==b){
        return "a=b";
    }
    else{
        return "NO";
    }
}
alert(f(1,3)+","+f(3,1)+","+f(3,3))