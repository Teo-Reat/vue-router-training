<template>
    <div>
        <h2>User Edit</h2>
        <p>Locale: {{ $route.query.locale }}</p>
        <p>Analytics: {{ $route.query.q }}</p>
        <div style="height: 700px"></div>
        <p id="data">Some extra Data</p>
    </div>
</template>