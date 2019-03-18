<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card">
                    <div class="card-header">Ejemplo 10 </div>

                    <div class="card-body">
                        
                        <input type="text" v-model="nombre">
                    </div>
                </div>
            </div>

        </div>
        <h1>hola {{nombre}}</h1>
    </div>
</template>

<script>
    export default {
        mounted() {
            console.log('Component mounted 2.')
        },data(){
            return{
                nombre:''
            }
        }
    }
</script>
