<template>
    <div id="app">
        <router-view />
    </div>
</template>

<script>
import AppHeader from "@/components/AppHeader.vue";
import AppSideBar from "./components/AppSideBar.vue";
export default {
    components: {
        AppHeader,
        AppSideBar,
    },
    mounted() {},
};
</script>

<style>
div#container {
    height: 100vh !important;
}

.table > :not(:first-child) {
    border-top-width: 1px !important;
}

span.label {
    padding: 0.5em 0.6em 0.3em;
    font-size: 75%;
    font-weight: bold;
    line-height: 1;
    color: #fff;
    text-align: center;
    white-space: nowrap;
    vertical-align: baseline;
    border-radius: 0.25em;
    margin-right: 0px;
    margin-bottom: 0px;
}

.b-form-datepicker .b-calendar-grid-weekdays,
.b-form-datepicker .b-calendar-grid-body > .row {
    margin: 0;
}

.b-form-datepicker label {
    display: none;
}
.date-input.form-control {
    width: 99px !important;
}

small.form-text {
    color: red !important;
}

.overflow-e {
    white-space: nowrap;
    width: 100%;
    overflow: hidden;
    text-overflow: ellipsis;
}

.form-duo {
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-gap: 0.5em;
}

.multi-select {
    display: grid;
    grid-auto-columns: 1fr;
    grid-gap: 0.5em;
}

.multi-select-row {
    display: grid;
    grid-template-columns: 1fr 12fr;
    align-items: center;
}
</style>
