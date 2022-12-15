<template>
    <div class="card border-0 side-nav">
        <div class="col-12">
            <p style="font-size:12px;">UNIVERSAL STUDIOS AT UNIVERSAL ORLANDO</p>
        </div>
        <ul class="side-tabs" role="tablist">
            <li class="nav-item">
                <a class="nav-link active" id="top-home-tab" data-bs-toggle="tab" href="#top-home" role="tab" aria-controls="top-home" aria-selected="true">
                    Summary
                </a>
            </li>
            <li class="nav-item">
                <a class="nav-link" id="top-home-tab" data-bs-toggle="tab" href="#top-home" role="tab" aria-controls="top-home" aria-selected="true">
                    Live Waiting Times
                </a>
            </li>
            <li class="nav-item">
                <a class="nav-link" id="top-home-tab" data-bs-toggle="tab" href="#top-home" role="tab" aria-controls="top-home" aria-selected="true">
                    Crowd Calendar
                </a>
            </li>
            <li class="nav-item">
                <a class="nav-link" id="top-home-tab" data-bs-toggle="tab" href="#top-home" role="tab" aria-controls="top-home" aria-selected="true">
                    Statistics
                </a>
            </li>
            <li class="nav-item">
                <a class="nav-link" id="top-home-tab" data-bs-toggle="tab" href="#top-home" role="tab" aria-controls="top-home" aria-selected="true">
                    Park Map
                </a>
            </li>
            <li class="nav-item">
                <a class="nav-link" id="top-home-tab" data-bs-toggle="tab" href="#top-home" role="tab" aria-controls="top-home" aria-selected="true">
                    Attendance
                </a>
            </li>
        </ul>
    </div>
</template>

<script>
export default {
    name: 'NavigationBar',
    props: {
        header:String
    },
    methods:{
        //active(href){
        //    if(this.header == href){
        //        return 'active';
        //    }
        //    return '';
        //}
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.side-nav{
    width: 225px;
    padding: 1em;
}
.side-tabs{
    list-style: none;
    margin: 0;
    padding: 0;
}
.nav-item a{
    border: 1px solid transparent;
    padding: 5px 30px 5px 0;
    border-radius: 5px;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
    -ms-flex-align: center;
    align-items: center;
    font-weight: 600;
}
.nav-item a svg{
    height: 18px;
    vertical-align: middle;
    margin-right: 5px;
}
.nav-link.active{
    color: #04AA6D;
}
</style>