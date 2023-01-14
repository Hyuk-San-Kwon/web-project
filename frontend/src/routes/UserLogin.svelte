<GoogleAuth clientId="905899780081-kka291u5e764hpcur3gt5ib7kr24o12p.apps.googleusercontent.com" on:auth-success={e => postlogin(e)} />
    <FacebookAuth appId="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" on:auth-success={e => console.dir(e.detail.user)} />
    
<script>
    import { GoogleAuth, FacebookAuth } from '@beyonk/svelte-social-auth'
    let data;
    function postlogin(e){
        console.log(e)
    }
    
</script>