<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card">
                    <div class="card-header">{{ header }}</div>

                    <div class="card-body">
                        {{ body }}
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
const header = "Laravel UI + Vue 3"
const body = "Aplicacion laravel 9 con autenticacion y Vue 3 + Vite.js y Bootstrap 5"
</script>
