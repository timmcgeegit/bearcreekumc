<script>
    import Header from "$lib/components/Header.svelte";
    import Footer from "$lib/components/Footer.svelte";
</script>

<Header />
<main class="font-sans bg-background-alt">
<section class="container mx-auto border-t-2 py-24">
    <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center">
         <div>
            <div class="text-5xl text-primary mb-4 font-serif font-bold">Get in Touch</div>
            <p class="text-xl leading-relaxed mb-4">Our experienced legal team is ready to assist you; reach out today to schedule a consultation and discuss how we can help protect your interests.</p>
            <div class="text-normal">
                <ul>
                    <li class="text-xl text-primary mb-1"><strong>McKenney | McClelland PLLC:</strong></li>
                    <li class="mb-2">2200 North Loop West, Suite 333<br>Houston, TX 77018</li>
                    <li class="mb-1">Office (713) 688-6767</li>
                    <li class="mb-1">Telefax (713) 688-0199</li>
                    <li class="mb-1">Quick Contact (713) 822-5490</li>
                    <li class="mb-1 border-b-2 inline-block hover:text-muted-foreground transition-all"><a href="mailto:hughleslie@hotmail.com">Email Hugh McKenney</a></li> 
                </ul>
            </div>
        </div>    
        <div class="container">
                    <img src="/mckenneylawmap.png" alt="McKenney Office on a map" class="rounded my-5">
        </div>    
</section>

<Footer />
</main>