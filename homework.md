console.log("Berapa jumlah dari tiap-tiap huruf dari suatu kata : "+ "hello world!  ")
let nama = 'hello world!'
let arrayname = nama.split('') // kalimat yand diubah menjadi setiap kata
let kata = arrayname.toString() //jadikan kata menjadi array
let count_h = 0
let count_e = 0
let count_l = 0
let count_o = 0
let count_spasi = 0
let count_w = 0
let count_r = 0
let count_d = 0
let count_seru = 0
for (let i = 0; i<kata.length; i++){
    if (kata [i] == "h"){
        count_h++
    } else if (kata [i] == "e"){
        count_e++
    } else if (kata [i] == "l"){
        count_l++
    } else if (kata [i] == "o"){
        count_o++
    }else if (kata [i] == " "){
        count_spasi++
    }else if (kata [i] == "w"){
        count_w++
    }else if (kata [i] == "r"){
        count_r++
    }else if (kata [i] == "d"){
        count_d++
    }else if (kata [i] == "!"){
        count_seru++
    }
}
console.log ("==============================")
console.log ("h : "+ count_h)
console.log ("e : "+ count_e)
console.log ("l : "+ count_l)
console.log ("o : "+ count_o)
console.log ("  : "+ count_spasi)
console.log ("w : "+ count_w)
console.log ("r : "+ count_r)
console.log ("d : "+ count_d)
console.log ("! : "+ count_seru)
console.log ("==============================")