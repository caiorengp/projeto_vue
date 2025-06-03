<template>
    <div>
        <h1>Olá meu nome é {{ nome }}, minha profissao é {{ profissao }} </h1>
    </div>
</template>
<script>
export default {
    name: "PrimeiroComponente",
    data() {
        return {
            nome: 'Caio',
            profissao: 'Programador',
        }
    }
}
</script>
