<script setup lang="ts">
import {Authenticator} from "@aws-amplify/ui-vue";
import "@aws-amplify/ui-vue/styles.css";

import Todos from './components/Todos.vue';
</script>

<template>
    <Authenticator>
        <main>
            <Todos/>
        </main>
    </Authenticator>
</template>

