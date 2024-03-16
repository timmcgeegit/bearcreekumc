<script lang="ts">
    import { AspectRatio } from "$lib/components/ui/aspect-ratio";
    import { Button } from "$lib/components/ui/button";
    import * as Card from "$lib/components/ui/card";
    import { Building } from 'lucide-svelte';
    import { Handshake } from 'lucide-svelte';
    import { BriefcaseBusiness } from 'lucide-svelte';
    import { PackageSearch } from 'lucide-svelte';
    import { BadgeDollarSign } from 'lucide-svelte';
    import { ArrowLeftRight } from 'lucide-svelte';
    import { Users } from 'lucide-svelte';
    import { ScrollText } from 'lucide-svelte';
    import { Umbrella } from 'lucide-svelte';
    import Header from "$lib/components/Header.svelte";
    import Footer from "$lib/components/Footer.svelte";
  </script>
  
  <svelte:head>
    <title>McKenney & Associates</title>
		<meta name="description" content="Hugh McKenney and the experienced legal team at McKenney & Associates PLLC provide skilled representation in property tax litigation, business law, and general practice matters throughout Texas. Trust our dedicated attorneys to protect your interests with personalized service and strategic solutions." />
  </svelte:head>
  
  <main class="font-sans bg-background-alt">
    <Header />
    <section class="bg-muted overflow-x-clip">
        <div class="container mx-auto grid grid-cols-1 md:grid-cols-2 gap-8 items-center">
          <div class="md:py-8 pt-16 pb-16">
            <h1 class="text-5xl lg:text-5xl text-primary font-bold mb-4 font-serif">Experienced Legal Representation</h1>
            <p class="text-xl leading-loose mb-8">We understand the difficulties and stress that you may face daily. Our team is here to provide superior legal advice with individual attention, communication, and dedicated personalized service.</p>
            <Button href="/contact" class="text-lg transition-all duration-300 hover:shadow-xl tracking-wide py-8 font-normal" aria-label="Request a consultation button">Request Consultation</Button>
          </div>
          <div class="relative">
            <div class="absolute ml-32 inset-0 bg-primary w-full h-full z-0"></div>
            <div class="relative z-10 -bottom-12 p-4">
                <AspectRatio ratio={3 / 4} class="bg-muted rounded">
                    <img
                      src="/OfficeArchitecturePatrickTomasso@0.5x.webp"
                      alt="Picture of a tall glass building"
                      class="h-full w-full shadow-lg rounded object-cover"
                    />
                  </AspectRatio>
                <!-- <img src="/OfficeArchitecturePatrickTomasso@0.5x.webp" alt="Corporate Legal Representation" class="rounded-lg aspect-w-2 aspect-h-3 shadow-lg"> -->
            </div>
          </div>
        </div>
      </section>
  
    <section class="container mx-auto my-24">
      <h2 class="text-5xl font-bold text-primary mb-4 font-serif">Areas of Focus</h2>
      <p class="text-xl max-w-xl leading-relaxed mb-8">Our firm specializes in property tax appraisal litigation, business law, and commercial litigation while offering a wide range of general legal services.</p>
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
        <div>
            <Card.Root class="transition-all ease-in-out h-full duration-500 hover:-translate-y-3 hover:shadow-xl shadow-lg pb-3">
                <img src="/McKenney_McClelland_Commercial.jpg" alt="Commerical Property" class="mb-6 rounded">
                <Card.Header class=" mb-3 py-0">
                <Card.Title class="text-primary text-2xl tracking-wide">Commercial Properties</Card.Title>
                </Card.Header>
                <Card.Content class="">
                <p>Our firm provides comprehensive legal services for commercial property owners, including property tax appeals, lease negotiations, and dispute resolution.</p>
                </Card.Content>
                </Card.Root>
        </div>
        <div>
            <Card.Root class="transition-all h-full ease-in-out duration-500 hover:-translate-y-3 hover:shadow-xl shadow-lg pb-3">
                <img src="/McKenney_McClelland_Multi-Use.jpg" alt="Multi-Use Property" class="mb-6 rounded">
                <Card.Header class=" mb-3 py-0">
                <Card.Title class="text-primary text-2xl tracking-wide">Multi-Use Properties</Card.Title>
                </Card.Header>
                <Card.Content class="">
                <p>We offer tailored legal solutions for multi-use properties, navigating the complex interplay of residential, commercial, and industrial regulations.</p>
                </Card.Content>
                </Card.Root>
        </div>
        <div>
            <Card.Root class="transition-all h-full ease-in-out duration-500 hover:-translate-y-3 hover:shadow-xl shadow-lg pb-3">
                <img src="/McKenney_McClelland_Residential.jpg" alt="Residential Property" class="mb-6 rounded">
                <Card.Header class=" mb-3 py-0">
                <Card.Title class="text-primary text-2xl tracking-wide">Residential Properties</Card.Title>
                </Card.Header>
                <Card.Content class="">
                <p>Our attorneys assist residential property owners with a range of legal matters, from property tax appeals to homeowners' association disputes and real estate transactions.</p>
                </Card.Content>
                </Card.Root>
        </div>
      </div>
    </section>
  
    <section class="container max-w-7xl">
        <div class="grid grid-cols-1 shadow-xl rounded overflow-hidden md:grid-cols-[70%_30%] items-center">
            <div class="h-full">
                <img src="/Mcdoor.png" alt="McKenney-door" class="object-cover w-full h-full">
            </div>  
            <div class="bg-primary h-full md:py-18 py-12 px-12 mx-auto text-primary-foreground">
                <h2 class="text-3xl font-bold mb-3 font-serif">About Us</h2>
                <p class="leading-relaxed mb-4 text-lg font-normal">McKenney | McClelland PLLC was created on January 1, 2001, from the remaining members of the previous firm McKenney & Jesse, P.C. which was formed in 1987 by Hugh L. McKenney and Joel Lee-Eric Jesse.</p>
                <a href="/about" class="text-lg px-1 border-b-2">Learn More</a>
            </div>
        </div>
    </section>
  
    <section class="container mx-auto my-24">
      <h2 class="text-5xl font-bold text-primary mb-4 font-serif">Areas of Practice</h2>
      <p class="text-xl max-w-xl leading-relaxed mb-8">Our firm provides skilled legal services in property tax appraisal litigation, commercial law, family law, probate, and more throughout Texas.</p>
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
       <!-- Property Tax Appraisal Litigation: -->
<Card.Root class="shadow-lg py-4 ">
    <Card.Header>
        <div class="text-primary pb-2"><Building size="45" /></div>
    <Card.Title class="text-primary text-2xl tracking-wide">Property Tax Appraisal Litigation</Card.Title>
    </Card.Header>
    <Card.Content>
    <p>We represent property owners throughout Texas in judicial appeals of property tax appraisals by appraisal districts.</p>
    </Card.Content>
    </Card.Root>
    
    <!-- Commercial & Business Litigation: -->
    <Card.Root class="shadow-lg py-4 ">
    <Card.Header>
        <div class="text-primary pb-2"><BriefcaseBusiness size="45" /></div>
    <Card.Title class="text-primary text-2xl tracking-wide">Commercial & Business Litigation</Card.Title>
    </Card.Header>
    <Card.Content>
    <p>Our attorneys handle various commercial and business litigation matters to protect our clients' interests.</p>
    </Card.Content>
    </Card.Root>
    
    <!-- Commercial & Business Transaction Representation: -->
    <Card.Root class="shadow-lg py-4">
    <Card.Header>
        <div class="text-primary pb-2"><Handshake size="45" /></div>
    <Card.Title class="text-primary text-2xl tracking-wide">Commercial & Business Transaction Representation</Card.Title>
    </Card.Header>
    <Card.Content>
    <p>We provide comprehensive legal representation for commercial and business transactions to ensure smooth operations.</p>
    </Card.Content>
    </Card.Root>
    
    <!-- Products Liability Plaintiff & Defense Work (non-personal injury): -->
    <Card.Root class="shadow-lg py-4">
    <Card.Header>
        <div class="text-primary pb-2"><PackageSearch size="45" /></div>
    <Card.Title class="text-primary text-2xl tracking-wide">Products Liability Plaintiff & Defense Work</Card.Title>
    </Card.Header>
    <Card.Content>
    <p>Our firm handles products liability cases for both plaintiffs and defendants, focusing on non-personal injury matters.</p>
    </Card.Content>
    </Card.Root>
    
    <!-- Business Sale & Acquisition Transactions: -->
    <Card.Root class="shadow-lg py-4">
    <Card.Header>
        <div class="text-primary pb-2"><BadgeDollarSign size="45" /></div>
    <Card.Title class="text-primary text-2xl tracking-wide">Business Sale & Acquisition Transactions</Card.Title>
    </Card.Header>
    <Card.Content>
    <p>We assist clients in navigating the complexities of business sale and acquisition transactions for a successful outcome.</p>
    </Card.Content>
    </Card.Root>
    
    <!-- Corporate Transactions: -->
    <Card.Root class="shadow-lg py-4">
    <Card.Header>
        <div class="text-primary pb-2"><ArrowLeftRight size="45" /></div>
    <Card.Title class="text-primary text-2xl tracking-wide">Corporate Transactions</Card.Title>
    </Card.Header>
    <Card.Content>
    <p>Our attorneys provide expert legal guidance for various corporate transactions to protect our clients' best interests.</p>
    </Card.Content>
    </Card.Root>
    
    <!-- Family Law: -->
    <Card.Root class="shadow-lg py-4">
    <Card.Header>
        <div class="text-primary pb-2"><Users size="45" /></div>
    <Card.Title class="text-primary text-2xl tracking-wide">Family Law</Card.Title>
    </Card.Header>
    <Card.Content>
    <p>We offer compassionate and skilled legal representation for a wide range of family law matters.</p>
    </Card.Content>
    </Card.Root>
    
    <!-- Wills and Trusts: -->
    <Card.Root class="shadow-lg py-4">
    <Card.Header>
        <div class="text-primary pb-2"><ScrollText size="45" /></div>
    <Card.Title class="text-primary text-2xl tracking-wide">Wills and Trusts</Card.Title>
    </Card.Header>
    <Card.Content>
    <p>Our firm helps clients create comprehensive estate plans, including wills and trusts, to ensure their wishes are fulfilled.</p>
    </Card.Content>
    </Card.Root>
    
    <!-- Insurance Defense: -->
    <Card.Root class="shadow-lg py-4">
    <Card.Header>
        <div class="text-primary pb-2"><Umbrella size="45" /></div>
    <Card.Title class="text-primary text-2xl tracking-wide">Insurance Defense</Card.Title>
    </Card.Header>
    <Card.Content>
    <p>We provide thorough and effective insurance defense services to protect the interests of insurance companies and their insureds.</p>
    </Card.Content>
    </Card.Root>
      </div>
    </section>
  
    <Footer />
    
  </main>
  
  <style global>
    /* Add any global styles here */
  </style>