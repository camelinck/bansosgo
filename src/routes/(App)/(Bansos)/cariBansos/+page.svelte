<script>
    import List from '../../../../lib/listBansos.svelte'
    import Search from '../../../../lib/searchBox.svelte'
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
<section id="courses" class="courses">
<div class="container" data-aos="fade-up">
<Search></Search>
</div>
<!-- ======= Courses Section ======= -->

    <div class="container" data-aos="fade-up">
        <div class="row" data-aos="zoom-in" data-aos-delay="100">
            <List></List>
            <List></List>
            <List></List>
        </div>
    </div>
</section>
<!-- End Courses Section -->
