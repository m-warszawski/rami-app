<template>
    <div class="card">
        <div class="card-body">
            <ul class="list-group">
                <li class="list-group-item">Adres e-amil</li>
                <li class="list-group-item">Numer telefonu</li>
                <li class="list-group-item">Adres do dostawy</li>
            </ul>
        </div>
        <div class="card-body">
            <button>Złóż zamówienie</button>
        </div>
    </div>
</template>

<style scoped>
.card {
    width: 60%;
    margin: 0 auto;
    background-color: var(--color-green);
}

.list-group-item {
    background-color: var(--color-green) !important;
}

@media screen and (max-width: 900px) {
    .card {
        width: 90%;
        margin: 0 auto;
    }
}
</style>
