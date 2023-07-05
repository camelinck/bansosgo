

<div class="pagetitle">
    <h1>Kelola Bantuan Sosial</h1>
    <nav>
        <ol class="breadcrumb">
            <li class="breadcrumb-item"><a href="index.html">Home</a></li>
            <li class="breadcrumb-item active">Kelola Bansos</li>
        </ol>
    </nav>
</div>
<!-- End Page Title -->

<section class="section">
    <a type="button" class="btn btn-info mb-3" href="/tambahBansos">Tambah</a>
    <div class="row">
        <div class="col-lg-12">
            <div class="card">
                <div class="card-body">
                    <h5 class="card-title">Data Program Bantuan Sosial</h5>
                    <div class="table-responsive">
                        <table class="table datatable">
                            <thead>
                                <tr>
                                    <th scope="col">No</th>
                                    <th scope="col">id_bantuan</th>
                                    <th scope="col">provinsi</th>
                                    <th scope="col">jenis_bantuan</th>
                                    <th scope="col">nama</th>
                                    <th scope="col">deskripsi</th>
                                    <th scope="col">gambar</th>
                                    <th scope="col">deadline</th>
                                    <th scope="col">created_at</th>
                                    <th>Aksi</th>
                                </tr>
                            </thead>
                            <tbody>
                                {#each bansos as bs}
                                    <tr>
                                        <th scope="row">1</th>
                                        <td>{bs.id_bantuan}</td>
                                        <td>{bs.id_provinsi}</td>
                                        <td>{bs.id_jenis_bantuan}</td>
                                        <td>{bs.nama}</td>
                                        <td class="cell-4"
                                            ><span class="text-overflow"
                                                >{bs.deskripsi}</span
                                            ></td
                                        >
                                        <td>{bs.gambar}</td>
                                        <td>{bs.tanggal_batas_pendaftaran}</td>
                                        <td>{bs.created_at}</td>
                                        <td
                                            ><span
                                                class="badge rounded-pill bg-warning text-dark"
                                                >Edit</span
                                            >
                                            <span
                                                class="badge rounded-pill bg-danger"
                                                >Hapus</span
                                            >
                                        </td>
                                    </tr>
                                {/each}
                            </tbody>
                        </table>
                    </div>
                    <!-- End Table with stripped rows -->
                </div>
            </div>
        </div>
    </div>
</section>
