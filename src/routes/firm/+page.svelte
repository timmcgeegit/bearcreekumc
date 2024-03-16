<script>
    import Header from "$lib/components/Header.svelte";
    import Footer from "$lib/components/Footer.svelte";
</script>

<Header />
<main class="font-sans bg-background-alt">
<section class="container mx-auto border-t-2 py-24">
    <div class="grid grid-cols-1 md:grid-cols-[60%_40%] gap-8">
        <div>
            <h2 class="text-6xl font-bold text-primary mb-4 font-serif">Our Firm</h2>
            <p class="text-xl leading-relaxed mb-4">A substantial part of the firm’s practice is devoted to representation of property owners throughout the state of Texas in judicial appeals of property tax appraisals by appraisal districts.</p>
            <p class="mb-4 text-lg">The firm continues to handle other matters related to general business representation, commercial litigation, and it continues to handle other matters associated with a general practice. The lawyers of the firm have substantial experience in matters in the following areas:</p>
            <ul class="list-disc ml-4 text-lg"> 
               <li>Property tax appraisal litigation</li> 
               <li>Commercial and business litigation</li> 
               <li>Commercial and business transaction representation</li> 
               <li>Products liability plaintiff and defense work (non-personal injury)</li> 
               <li>Personal injury</li> 
               <li>Business sale and acquisition transactions</li> 
               <li>Corporate transactions</li> 
               <li>Family law</li> 
               <li>Probate and estate law (including wills and trusts)</li> 
               <li>Insurance defense</li> 
            </ul>
        </div>
        <div class="lg:container">
            <div class="container py-16 bg-primary rounded h-full">
                <div class="text-4xl text-background-alt mb-5 font-serif font-bold">Get in Touch</div>
                <div class="text-normal text-white">
                    <ul>
                        <li class="text-lg mb-1"><strong>McKenney | McClelland PLLC:</strong></li>
                        <li class="mb-2">2200 North Loop West, Suite 333<br>Houston, TX 77018</li>
                        <li class="mb-2">Office (713) 688-6767</li>
                        <li class="mb-2">Telefax (713) 688-0199</li>
                        <li class="mb-2">Quick Contact (713) 822-5490</li>
                        <li class="mb-2 border-b-2 inline-block hover:text-muted transition-all"><a href="mailto:hughleslie@hotmail.com">Email Hugh McKenney</a></li> 
                    </ul>
                <div>
                    <img src="/mckenneylawmap.png" alt="McKenney Office on a map" class="rounded my-5">
                </div>    
                <div>
                    <div class="text-3xl text-background-alt font-serif mb-3 mt-8">Areas of Practice</div>
                    <ul class="text-sm list-disc ml-2">
                        <li class="mb-1">Property Tax Appraisal Litigation</li>
                        <li class="mb-1">Commercial & Business Litigation</li>
                        <li class="mb-1">Commercial & Business Transaction Representation</li>
                        <li class="mb-1">Products Liability Plaintiff & Defense Work (non-personal injury)</li>
                        <li class="mb-1">Business Sale & Acquisition Transactions</li>
                        <li class="mb-1">Corporate Transactions</li>
                        <li class="mb-1">Family Law</li>
                        <li class="mb-1">Wills and Trusts</li>
                        <li class="mb-1">Insurance Defense</li>
                    </ul>
                </div>

                </div>
            </div>

        </div>
    </div>
</section>

<Footer />
</main>