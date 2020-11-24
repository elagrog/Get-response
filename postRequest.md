

curl -H "Content-Type: application/json" -X POST -d'{
   "mealType":"lunch",
   "mealCat":{
  	"main":"burgerMeal",
  	"burger":{
     	"pattyType":"”beef”",
     	"pattyQty":1,
     	"pattyWeightG":300,
     	"pattyCook":"MR",
     	"bunType":"whiteBread",
     	"condiment1":"ketchup",
     	"condiment2":"secretSauce",
          "condiment3":"mayonnaise
     	"topping1":"lettuce",
          "topping2":"cucumber",
     	"topping3":"tomato",
     	"topping4":"pickledOnion",
     	"topping5":"cheddarCheese"
  	},
  	"sides":{
     	"side1":{
          "type":"soup",
          "size":"small"
          },
          "side2":{
        	"type":"frenchFries",
        	"size":"small"
     	},
     	"side3":{
        	"type":"crispyOnionRings",
        	"size":"big"
     	}
  	},
  	"drink":{
     	"type":"Coke",
     	"size":"large",
     	"ice":"yes"
  	}
   }
}'
http://URL/





