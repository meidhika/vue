<template>
<span>{{this.prefix + Number.parseFloat(value).toFixed(precision)}}</span>
</template>
<script>
export default{
    props: {
        value: Number,
        prefix: {
            type: String,
            default: 'Rp'
        },
        precision: {
            type: Number,
            default: 2
        }
    },
}
</script>
