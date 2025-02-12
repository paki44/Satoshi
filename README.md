const array = [1, 2, 3, 4, 5];
const doubled = array.map(num => num * 2);
console.log(doubled); // [2, 4, 6, 8, 10]

const sum = array.reduce((acc, curr) => acc + curr, 0);
console.log(sum); // 15
