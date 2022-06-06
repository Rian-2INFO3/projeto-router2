<template>
  <div class="container">
    <div class="title">
<<<<<<< HEAD
      <h2>Gerenciamento de times</h2>
=======
      <h2>Gerenciamento de Times</h2>
>>>>>>> c1efd786da965a8aa0e66494dec04bb1a98bbfd5
    </div>
    <div class="form-input">
      <input type="text" />
      <button>Salvar</button>
    </div>
<<<<<<< HEAD
    <div id="list-times">
=======
    <div class="list-times">
>>>>>>> c1efd786da965a8aa0e66494dec04bb1a98bbfd5
      <table>
        <thead>
          <tr>
            <th>ID</th>
            <th>Nome</th>
            <th>Ações</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>1</td>
<<<<<<< HEAD
            <td>Time 1</td>
=======
            <td>Time</td>
>>>>>>> c1efd786da965a8aa0e66494dec04bb1a98bbfd5
            <td>???</td>
          </tr>
          <tr>
            <td>2</td>
            <td>Time 2</td>
            <td>???</td>
          </tr>
          <tr>
            <td>3</td>
            <td>Time 3</td>
            <td>???</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
<<<<<<< HEAD
</template>
<style>
h2 {
  font-weight: normal;
}

th {
  font-weight: normal;
}

=======
  <RouterView />
</template>

<style>
>>>>>>> c1efd786da965a8aa0e66494dec04bb1a98bbfd5
.title {
  text-align: center;
  margin: 2rem 0;
}
<<<<<<< HEAD
.form-input {
  height: 40px;
=======

.form-input {
>>>>>>> c1efd786da965a8aa0e66494dec04bb1a98bbfd5
  display: flex;
  justify-content: center;
  margin: 2rem 0;
}

.form-input input {
  width: 50%;
  padding: 0.5rem;
<<<<<<< HEAD
  border: 1px solid #ccc;
=======
  border: 5px solid #98b7e1;
>>>>>>> c1efd786da965a8aa0e66494dec04bb1a98bbfd5
  border-radius: 10px;
}

.form-input button {
  padding: 0.5rem;
<<<<<<< HEAD
  width: 15%;
  border: 1px solid #431766;
  border-radius: 10px;
  background-color: #7910b6;
  font-weight: bold;
  margin-left: 1%;
  color: #d2d2c9;
}

.form-input button:hover {
  background-color: #f088a0;
=======
  border: 5px solid #98b7e1;
  border-radius: 10px;
  color: #454663;
  font-weight: bold;
  margin-left: 1%;
>>>>>>> c1efd786da965a8aa0e66494dec04bb1a98bbfd5
}

.list-times {
  display: flex;
  justify-content: center;
}

table {
<<<<<<< HEAD
  width: 50%;
  border-collapse: collapse;
  margin: 0 auto;
  border: 1px solid black;
=======
  width: 80%;
  border-collapse: collapse;
  margin: 0 auto;
  border: 1px solid #9bfae2;
>>>>>>> c1efd786da965a8aa0e66494dec04bb1a98bbfd5
  font-size: 1.1rem;
  text-align: center;
}

table thead {
<<<<<<< HEAD
  background-color: #d6d6d6;
  color: rgb(0, 0, 0);
}

table tbody tr:nth-child(odd) {
  background-color: #b906f0;
=======
  background-color: #98b7e1;
  color: #454663;
}

table thead th {
  font-weight: bolder;
}

table tbody tr:nth-child(odd) {
  background-color: #4f374d;
>>>>>>> c1efd786da965a8aa0e66494dec04bb1a98bbfd5
}
</style>
