body,
img,
h1,
h2,
h3,
li {
  margin: 0;
}

body {
  height: 100%;
  line-height: 1.5;
  flex-direction: column;
  -webkit-font-smoothing: antialiased;
  -moz-osx-smoothing: grayscale;
  display: flex;
}

li,
p,
td {
  font-family: "Outfit";
  font-size: 16px;
}

h2 {
  font-family: "Young Serif";
  font-size: 24px;
  font-weight: 400;
}

li::marker {
  color: hsl(14, 45%, 36%);
  font-weight: bold;
}

table {
  border-collapse: collapse;
  width: 100%;
  line-height: 2;
}
tr {
  border-bottom: 1px solid rgb(224, 224, 224);
}
tr:last-child {
  border-bottom: none;
}

hr {
  color: hsl(0, 0%, 85%);
}

section {
  flex: 1;
}
