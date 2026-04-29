# My-first-repor
hello mai abhi GitHub Sikh rahi hun.
<table>
  <tr>
    <td>dates</td>
    <td>rupees</td>
  </tr>
  <tr>
  <td>20/03/2026</td>
  <td>20</td>
    </tr>
  <tr>
    <td>21/03/2026</td>
    <td>20</td>
    </tr>
  <tr>
    <td>22/03/2026</td>
    <td>20</td>
  </tr>
</table>
<script>
let dates = ["20/03/2026", "21/03/2026", "22/03/2026"];
let rupees = [20, 20, 20];

let table = document.getElementById("myTable");

for (let i = 0; i < dates.length; i++) {
  let row = `<tr>
               <td>${dates[i]}</td>
               <td>${rupees[i]}</td>
             </tr>`;
  table.innerHTML += row;
}
</script>
