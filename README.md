# test
console.log("1");
var s = "*****************************";
console.log(s.substring([0],[9]));
console.log(s.substring([0],[17]));
console.log(s.substring([0],[23]));
console.log(s.substring([0],[27]));
console.log(s.substring([0],[29]));
console.log(s.substring([0],[29]));
console.log(s.substring([0],[27]));
console.log(s.substring([0],[23]));
console.log(s.substring([0],[17]));
console.log(s.substring([0],[9]));

console.log("2");
for(var st = "*" ; st.length < 29 ; st += "*") {
    //   st.length ===9 ? st.length == 9 : console.log(st);
    if (st.length === 9) {
        console.log(st);
    }
    else if (st.length === 17) {
        console.log(st);
    }
}
for(var st = "*" ; st.length <= 29 ; st += "*") {
    if (st.length === 23) {
        console.log(st);
    }
    else if (st.length === 27) {
        console.log(st);
    }
    else {
        if (st.length === 29) {
            console.log(st);
            console.log(st);
        }
    }
}
for(var st = "*" ; st.length < 29; st += "*") {
    if (st.length === 27) {
        console.log(st);
    }
}
for(var st = "*" ; st.length < 24; st += "*") {
    if (st.length === 23) {
        console.log(st);
    }
}
for(var st = "*" ; st.length < 18; st += "*") {
    if (st.length === 17) {
        console.log(st);
    }
}
for(var st = "*" ; st.length < 10; st += "*") {
    if (st.length === 9) {
        console.log(st);
    }
}

