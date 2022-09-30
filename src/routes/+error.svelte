<script context="module">
	export async function load(/*{ error }*/) {
        await new Promise(resolve => setTimeout(resolve, 1000))
		return {
			props: { message: 
                'O que você procura não está por aqui...' 
            }
		};
	}
</script>

<script>
    export let message;
</script>


<div class="error">
    <h2>Ooops!</h2>
    <p>{message}</p>
    <a href="/">Ir para o Início</a>
</div>


<style>
    .error {
        text-align: center;
        margin-bottom: 60px;
    }
</style>