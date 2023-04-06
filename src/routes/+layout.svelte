<div class="background">

    <div class="layout">
        <slot/>
    </div>
</div>

<style>
    .background {
        padding: 32px; 

        position: absolute;
        inset: 0;

        background-color: darkcyan;
    }

    .layout {
        width: 100%;
        Max-width: 900px; 
        margin: 0 auto; 
    }
</style>