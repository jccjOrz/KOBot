<template>
    <div class="container content-field">
        <div class="card">
            <div class="card-body">
                <slot></slot>
                <!-- 填充的都在slot里面 -->
            </div>
        </div>
    </div>
</template>

<script>
</script>

<style scoped>
div.content-field{
    margin-top: 20px;
}
div.card{
    background:  rgba(0,0,0,0.0);
    
}

</style>