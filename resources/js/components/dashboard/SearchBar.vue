<template>
    <div class="input-group input-group-seamless-append">
        <input
            type="text"
            id="dashboard__searchbar"
            class="form-control"
            ref="search"
            v-model="search"
        >

        <logo
            v-if="!search"
            class="position-absolute logo--placeholder"
            :responsive="true"
        />

        <div class="input-group-append">
            <div
                id="dashboard__search-icon"
                class="input-group-text bg-white"
                @click="focusSearch"
            >
                <i class="fa fa-search"></i>
            </div>
        </div>
    </div>
</template>

<script>
    import Logo from '@js/components/Logo';

    export default {
        components: {Logo},

        data: _=> ({
            search: ''
        }),

        methods: {
            focusSearch() {
                this.$refs.search.focus();
            }
        }
    }
</script>
