<template>
    <section class="sectionHomeComponent">
        <div class="jumbotron jumbotron-fluid">
            <div class="container">
                <h1 class="display-4">Fluid jumbotron</h1>
                <p class="lead">This is a modified jumbotron that occupies the entire horizontal space of its parent.</p>
            </div>
        </div>

        <div class="container">
            <div class="row">
                <div class="col-sm-12">
                    <h1>asdadad</h1>
                </div>
            </div>
        </div>

    </section>
</template>

<style>
    .sectionHomeComponent{
        margin-top: -25px;
    }

    .sectionHomeComponent .jumbotron{
        /*background-image: ;*/
    }
</style>

<script>
    export default {
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
