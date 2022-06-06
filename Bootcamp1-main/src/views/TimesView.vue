<template>
  <div class="container">
    <div class="title">
        <h2>Gerenciamento de time</h2>
      </div>
    <div class="form-input">
      <input type="text" /> 
      <button>Salvar</button>
    </div>
    <div class="list-times">
      <table>
        <thead>
          <tr>
            <th>ID</th>
            <th>nome</th>
            <th>Açoes</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>1</td>
            <td>Time1</td>
            <td>???</td>
          </tr>
           <tr>
            <td>2</td>
            <td>Time2</td>
            <td>???</td>
          </tr>
           <tr>
            <td>3</td>
            <td>Time3</td>
            <td>???</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</template>

<style>

  

  .title {
    margin-top: 2rem;
    display: flex;
    justify-content: center;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    color: coral;
  }

  .form-input {
      margin-top: 10px;
      display: flex;
      justify-content: center;
  }

  .form-input input {
    width: 60%;
    height: 40px;
    border:1 px solid #ccc;
    border-radius: 10px;
    padding: 0 10px;
  }

  .form-input button {
    color: rgb(34, 32, 28);
    height: 42.5px;
    width: 200px;
    background-color: gray;
    font-family: 'Courier New', Courier, monospace;
    border-radius: 10px;
    cursor: pointer;
    margin-left: 10px;
  }

  .list-times {
    display: flex;
    justify-content: center;
  }

  table {
    width: 80%;
    margin: 2% auto;
    border-collapse: collapse ;
  }

  table tr th {
    border: 1px solid #ccc;
    padding: 10px ;
    font-weight: 10px;
  }

  table tr td {
    border: 1px solid #ccc;
    padding: 10px;
  }

  table tr:nth-child(even) {
    background-color: #ccc;
  }
</style>