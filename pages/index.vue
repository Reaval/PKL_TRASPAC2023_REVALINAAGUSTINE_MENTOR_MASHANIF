<template>
  <div class="biodata">
    <h1 style="text-align: center"><b>TUGAS</b></h1>
    <table class="bionuxt" align="center">
      <thead>
        <tr>
          <th colspan="3" class="bio">BIODATA</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Nama</td>
          <td>Revalina Agustine</td>
          <td rowspan="7">
            <img
              src="https://pbs.twimg.com/profile_images/1370022873809645571/jo32MjlR_400x400.jpg"
              width="170px"
              height="200px"
              alt="profile"
            />
          </td>
        </tr>
        <tr>
          <td>Umur</td>
          <td>17 Tahun</td>
        </tr>
        <tr>
          <td>Jenis Kelamin</td>
          <td>Perempuan</td>
        </tr>
        <tr>
          <td>Golongan Darah</td>
          <td>B</td>
        </tr>
        <tr>
          <td>Tempat/tanggal lahir</td>
          <td>Jakarta,31 Agustus 2005</td>
        </tr>
        <tr>
          <td>Alamat</td>
          <td>
            Jln.Perintis Kemerdekaan RT. 007 RW 02 No.70 Kel.Pulogadung
            Kec.Pulogadung
          </td>
        </tr>
        <tr>
          <td>Sekolah</td>
          <td>SMK Negeri 71 Jakarta</td>
        </tr>
      </tbody>
    </table>
  </div>
</template>

<style>
table,
th,
td,
tr {
  border: 1px solid black;
  border-collapse: collapse;
}
.bio {
  text-align: center;
  background-color: royalblue;
  color: white;
}
</style>

<script>
export default {
  name: "IndexPage",
};
</script>
