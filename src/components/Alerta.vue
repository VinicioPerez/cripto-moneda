<template>
    <div class="alerta">
        <slot></slot>
    </div>
</template>

<style>
    .alerta {
        text-align: center;
        margin-bottom: 2rem;
        color: var(--blanco);
        background-color: rgb(214, 19, 19);
        text-transform: uppercase;
        font-weight: 700;
        font-size: 1.4rem;
        padding: 1rem;
        border-radius: 1.5rem;
    }
</style>