# Atsiskaitymas-FUNKCIJOS
Js Atsiskaitymas: FUNKCIJOS
1 Uzduotis 
function Keistiy(text) {
    if (text.length === 0) return text;
    return 'Y' + text.slice(1);
}

Pavizdys
console.log(Keistiy("hello")); 



2. Uzduotis

   function keitimas(word) {
    return word.toLowerCase();
}

Pavizdys
console.log(keitimas("HELLO")); 

3.function Numeris(number) {
    return number % 2 !== 0;
}

console.log(Numeris(3)); 
console.log(Numeris(4)); 
