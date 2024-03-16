<script lang="ts">
    import { Button } from "$lib/components/ui/button";
    import * as Sheet from "$lib/components/ui/sheet";
    import { Menu } from 'lucide-svelte';
</script>

<header>
<nav class="bg-background-alt text-foreground px-4 py-8">
    <div class="container mx-auto flex justify-between items-center">
      <div class="flex flex-row items-center justify-between gap-5">
      <div>
      <a href="/" class="md:text-3xl text-2xl text-primary font-bold font-serif">McKenney & Associates</a>
      </div>
      <div style="">
        <Sheet.Root class="">
          <Sheet.Trigger class="lg:hidden items-center pt-3"><Menu /></Sheet.Trigger>
          <Sheet.Content>
            <Sheet.Header>
              <Sheet.Title></Sheet.Title>
              <Sheet.Description>
                <ul class="text-lg">
                  <li class="mb-3"><a href="/firm" class="mx-4 text-foreground hover:text-primary">Our Firm</a></li>
                  <li class="mb-3"><a href="/about" class="mx-4 text-foreground hover:text-primary">About Us</a></li>
                  <li class="mb-3"><a href="/contact" class="mx-4 text-foreground hover:text-primary">Contact</a></li>
                </ul>
                <Button href="/contact" class="text transition-all duration-300 hover:shadow-xl tracking-wide py-6 font-normal">Request Consultation</Button>
              </Sheet.Description>
            </Sheet.Header>
          </Sheet.Content>
        </Sheet.Root>
      </div>  
      <div class="text-lg hidden lg:block pt-2">
        <a href="/firm" class="mx-4 text-foreground hover:text-primary active:text-primary">Our Firm</a>
        <a href="/about" class="mx-4 text-foreground hover:text-primary active:text-primary">About Us</a>
        <a href="/contact" class="mx-4 text-foreground hover:text-primary active:text-primary">Contact</a>
      </div>
    </div>
      <Button href="/contact" class="text-lg hidden lg:flex transition-all duration-300 hover:shadow-xl tracking-wide py-8 font-normal">Request Consultation</Button>
      <!-- <Button size="lg" href="tel:123-456-7890" class="text-lg tracking-wide font-normal py-4">Call Us: 123-456-7890</Button> -->
      <!-- <a href="tel:123-456-7890" class="bg-primary text-primary-foreground font-bold py-2 px-4 rounded">Call Us: 123-456-7890</a> -->
    </div>
  </nav>
</header>