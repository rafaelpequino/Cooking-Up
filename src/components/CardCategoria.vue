<script lang="ts">
import type ICategoria from '@/Interfaces/ICategoria';
import type { PropType } from 'vue/dist/vue.js';

export default {
    props: {
        categoria: { type: Object as PropType<ICategoria>, required: true }
    }
}
</script>

<template>
    {{ categoria.nome }}
    {{ categoria.imagem }}
</template>