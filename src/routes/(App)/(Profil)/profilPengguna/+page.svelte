<script>
    import Overview from '../../../../lib/overview.svelte'
    import EditProfil from '../../../../lib/editProfil.svelte'
    import Riwayat from '../../../../lib/riwayat.svelte'
  </script>
  
 <!-- ======= Breadcrumbs ======= -->
<div class="breadcrumbs">
    <div class="container">
        <h2>Courses</h2>
        <p>
            Est dolorum ut non facere possimus quibusdam eligendi voluptatem.
            Quia id aut similique quia voluptas sit quaerat debitis. Rerum omnis
            ipsam aperiam consequatur laboriosam nemo harum praesentium.
        </p>
    </div>
</div>
<!-- End Breadcrumbs -->
 <section class="section profile">
    <div class="row">
      <div class="col-xl-4">
        <div class="card">
          <div
            class="card-body profile-card pt-4 d-flex flex-column align-items-center"
          >
            <img
              src="assets/img/profile-img.jpg"
              alt="Profile"
              class="rounded-circle"
            />
            <h2>Kevin Anderson</h2>
            <h3>Web Designer</h3>
            <div class="social-links mt-2">
              <a href="#" class="twitter"><i class="bi bi-twitter" /></a>
              <a href="#" class="facebook"><i class="bi bi-facebook" /></a>
              <a href="#" class="instagram"><i class="bi bi-instagram" /></a>
              <a href="#" class="linkedin"><i class="bi bi-linkedin" /></a>
            </div>
          </div>
        </div>
      </div>
  
      <div class="col-xl-8">
        <div class="card">
          <div class="card-body pt-3">
            <!-- Bordered Tabs -->
            <ul class="nav nav-tabs nav-tabs-bordered">
              <li class="nav-item">
                <button
                  class="nav-link active"
                  data-bs-toggle="tab"
                  data-bs-target="#profile-overview">Overview</button
                >
              </li>
  
              <li class="nav-item">
                <button
                  class="nav-link"
                  data-bs-toggle="tab"
                  data-bs-target="#profile-edit">Edit Profile</button
                >
              </li>
  
              <li class="nav-item">
                <button
                  class="nav-link"
                  data-bs-toggle="tab"
                  data-bs-target="#profile-settings">Settings</button
                >
              </li>
            </ul>
            <div class="tab-content pt-2">
              <Overview />
              <EditProfil />
              <Riwayat />
            </div>
            <!-- End Bordered Tabs -->
          </div>
        </div>
      </div>
    </div>
  </section>
  