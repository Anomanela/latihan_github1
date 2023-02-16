let input = 699
let angka = input.toString()
console.log ("Nilai yang diinput : "+ angka)
let count_angka = 0
for (let i = 0; i< angka.length; i++){
    count_angka++
}

if (count_angka == 1){
    console.log ("Nilai tersebut merupakan = satuan")
}else if (count_angka == 2){
    console.log ("Nilai tersebut merupakan = puluhan")
}else if (count_angka == 3){
    console.log ("Nilai tersebut merupakan = ratusan")
}else if (count_angka == 4){
    console.log ("Nilai tersebut merupakan = ribuan")
}else if (count_angka == 5){
    console.log ("Nilai tersebut merupakan = puluh ribuan")
}else {
    console.log ("input tidak valid")
}
