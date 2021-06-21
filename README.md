1.a.   var obj = [
            { person: "Name 1", age: "2", company: "GUVI" },
            { person: "Name 2", age: "5", company: "GUVI geek" },
            { person: "Name 3", age: "8", company: "GUVI geek network" },
          ];
        for(var i in obj)
        console.log(obj[i]);
        
   b.  var obj = [
            { person: "Name 1", age: "2", company: "GUVI" },
            { person: "Name 2", age: "5", company: "GUVI geek" },
            { person: "Name 3", age: "8", company: "GUVI geek network" },
          ];
        for(var i=0;i<obj.length;i++)
        console.log(obj[i]);

  c.  var obj = [
            { person: "Name 1", age: "2", company: "GUVI" },
            { person: "Name 2", age: "5", company: "GUVI geek" },
            { person: "Name 3", age: "8", company: "GUVI geek network" },
          ];
        for(var element of obj)
        console.log(obj);

  d.  var obj = [
            { person: "Name 1", age: "2", company: "GUVI" },
            { person: "Name 2", age: "5", company: "GUVI geek" },
            { person: "Name 3", age: "8", company: "GUVI geek network" },
          ];
       obj.forEach(element => console.log(element));
