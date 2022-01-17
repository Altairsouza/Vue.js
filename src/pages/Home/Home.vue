<template>
    <div>
        
    <navBarComponent />
    <mainComponent />
    <paralaxComponent />
    <planosComponent />
    <parallax2Component />
    <SolucoesComponent />
    <footerComponent />
    </div>
</template>

<script>
import navBarComponent from '@/pages/Home/components/navBarComponent.vue'
import mainComponent from '@/pages/Home/components/mainComponent.vue'
import paralaxComponent from '@/pages/Home/components/paralaxComponent.vue'
import planosComponent from "@/pages/Home/components/planosComponent"
import parallax2Component from "@/pages/Home/components/parallax2Component"
import SolucoesComponent from "@/pages/Home/components/SolucoesComponent"
import footerComponent from "@/pages/Home/components/footerComponent"

export default {
    name: 'Home',
    components: {
        navBarComponent,
        mainComponent,
        paralaxComponent,
        planosComponent,
        parallax2Component,
        SolucoesComponent,
        footerComponent,
    }
}

</script>

<style >
/* Gerais*/

body {
    font-family: 'roboto', sans-serif ;
}

.row {
    margin: 0;
}


.container {
    padding: 70px 0;

}
</style>