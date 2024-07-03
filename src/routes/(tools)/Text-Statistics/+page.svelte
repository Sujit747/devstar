<script>

</script>

<div class="card gap-16 items-center mx-auto max-w-screen-xl lg:grid lg:grid-cols-2 overflow-hidden rounded-lg">
	<!-- Add tool here -->
</div>

<style>
  body {
    font-family: 'Arial', sans-serif;
    background: #1A1A1A;
    color: #F5F5F5;
  }
  .container {
    max-width: 100%;
  }
  .card {
    /* background-color: #2A2A2A; */
    border-radius: 0.5rem;
    box-shadow: rgba(0, 0, 0, 0.1) 0 0 0 2px;
    padding: 1rem;
    margin-top: 1rem;
  }
  textarea {
    width: 100%;
    padding: 0.5rem;
    border: 1px solid #4A4A4A;
    border-radius:0.375rem;
      resize: none;
      outline: none;
      /* background-color: #1A1A1A; */
      /* color: #F5F5F5; */
    }
    textarea:focus {
      border-color: #3B82F6;
    }
    button {
      display: inline-block;
      padding: 0.5rem 1rem;
      background-color: #3B82F6;
      color: white;
      border: none;
      border-radius: 0.375rem;
      cursor: pointer;
      transition: background-color 0.3s;
    }
    button:hover {
      background-color: #2563EB;
    }
    .text-lg {
      font-size: 1.125rem;
    }
    .font-bold {
      font-weight: 700;
    }
    table {
      width: 100%;
      /* border-collapse: collapse;  */
      border-radius: 0.12em;
    }
    th, td {
      border: 1px solid #4A4A4A;
      padding: 0.5rem;
      text-align: left;
    }
    th {
      /*background-color: #3B82F6;*/
    }
    tr:nth-child(even) {
      /*background-color: #333;*/
    }
    @media (min-width: 640px) {
      .container {
        max-width: 640px;
      }
    }
    @media (min-width: 768px) {
      .container {
        max-width: 768px;
      }
    }
    @media (min-width: 1024px) {
      .container {
        max-width: 1024px;
      }
    }
</style>
