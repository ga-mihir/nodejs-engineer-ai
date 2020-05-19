# nodejs-engineer-ai
clone repo
npm install
replace .env.example with .env
node app.js

In postman 


Route ---> http://localhost:8105/api/v1/sudoku
Method POST 
Payload --> {
	"data":[
  null, null, null, null, 7, null, 4, 1, null,
  null, null, null, null, null, null, 5, null, null,
  6, null, 2, null, null, 1, null, 8, null,
  null, 4, 6, null, 1, null, null, null, null,
  null, null, null, 4, null, null, null, null, null,
  3, 8, null, null, null, 2, null, null, null,
  null, null, null, 5, null, null, 3, null, 0,
  null, null, null, null, 6, 7, null, null, 5,
  null, 0, null, null, null, null, null, 7, null
]
}

output --> {
    "success": true,
    "message": "Sudoku Created Successfully !!!",
    "data": {
        "finalResult": [
            8,
            3,
            9,
            2,
            7,
            5,
            4,
            1,
            6,
            1,
            7,
            4,
            3,
            8,
            6,
            5,
            2,
            9,
            6,
            5,
            2,
            9,
            4,
            1,
            7,
            8,
            3,
            2,
            4,
            6,
            7,
            1,
            3,
            9,
            5,
            8,
            9,
            1,
            7,
            4,
            5,
            8,
            6,
            3,
            2,
            3,
            8,
            5,
            6,
            9,
            2,
            1,
            4,
            7,
            7,
            9,
            8,
            5,
            2,
            4,
            3,
            6,
            0,
            4,
            2,
            3,
            1,
            6,
            7,
            8,
            9,
            5,
            5,
            0,
            1,
            8,
            3,
            9,
            2,
            7,
            4
        ]
    }
}