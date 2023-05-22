<script>
export default {
  name: "Home",
  props: {
    msg: String,
  },
};
</script>

<template>
  <div>
    <h1>Liste des articles</h1>
    <table class="data-table">
      <thead>
        <tr>
          <th>ID</th>
          <th>Name</th>
          <th>Email</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>1</td>
          <td>John Doe</td>
          <td>johndoe@example.com</td>
        </tr>
        <tr>
          <td>2</td>
          <td>Jane Smith</td>
          <td>janesmith@example.com</td>
        </tr>
        <tr>
          <td>2</td>
          <td>Jane Smith</td>
          <td>janesmith@example.com</td>
        </tr>
        <tr>
          <td>2</td>
          <td>Jane Smith</td>
          <td>janesmith@example.com</td>
        </tr>
        <tr>
          <td>2</td>
          <td>Jane Smith</td>
          <td>janesmith@example.com</td>
        </tr>
        <tr>
          <td>2</td>
          <td>Jane Smith</td>
          <td>janesmith@example.com</td>
        </tr>
        <tr>
          <td>2</td>
          <td>Jane Smith</td>
          <td>janesmith@example.com</td>
        </tr>
        <!-- Add more table rows as needed -->
      </tbody>
    </table>
  </div>
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.grid-container {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  grid-gap: 30px;
}
.data-table {
  width: 100%;
  border-collapse: collapse;
}

.data-table th,
.data-table td {
  padding: 10px;
  border: 1px solid #ddd;
}

.data-table th {
  background-color: #f0f0f0;
  text-align: left;
}

.data-table tbody tr:nth-child(even) {
  background-color: #f9f9f9;
}

.data-table tbody tr:hover {
  background-color: #e5e5e5;
}
</style>
