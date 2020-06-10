<script>
    export let displayName;
    export let photoURL;
    export let uid;
</script>

<h3>Hi {displayName}</h3>

<img src={photoURL} width="100" alt="{displayName}'s avatar'" />
<p>Your user ID is {uid}.</p>
