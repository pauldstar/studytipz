<template>
    <form-page :logo="false">
        <form @submit.prevent="$router.push('/dashboard/verify-step-2')" class="identity-upload">
            <div class="identity-content">
                <span class="icon"><i class="fa fa-shield"></i></span>
                <h4>Please verify your identity before adding your card</h4>
                <p>Uploading your ID helps as ensure the safety and security of your founds</p>
            </div>

            <div class="text-center">
                <button type="submit" class="btn btn-success pl-5 pr-5">Upload ID</button>
            </div>
        </form>
    </form-page>
</template>

<script>
    import formPage from '@js/components/FormPage';

    export default {
        components: {formPage}
    }
</script>
