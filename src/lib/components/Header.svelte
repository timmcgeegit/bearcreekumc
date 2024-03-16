<script lang="ts">
    import { Button } from "$lib/components/ui/button";
</script>

<header>
<nav class="bg-background-alt text-foreground px-4 py-8">
    <div class="container mx-auto flex justify-between items-center">
      <div class="flex flex-row items-center justify-between gap-16">
      <div>
      <a href="/" class="text-3xl text-primary font-bold font-serif">McKenney & Associates</a>
      </div>  
      <div class="text-lg">
        <a href="/firm" class="mx-4 text-foreground">Our Firm</a>
        <a href="/about" class="mx-4 text-foreground">About Us</a>
        <a href="/contact" class="mx-4 text-foreground">Contact</a>
      </div>
    </div>
      <Button href="/contact" class="text-lg transition-all duration-300 hover:shadow-xl tracking-wide py-8 font-normal">Request Consultation</Button>
      <!-- <Button size="lg" href="tel:123-456-7890" class="text-lg tracking-wide font-normal py-4">Call Us: 123-456-7890</Button> -->
      <!-- <a href="tel:123-456-7890" class="bg-primary text-primary-foreground font-bold py-2 px-4 rounded">Call Us: 123-456-7890</a> -->
    </div>
  </nav>
</header>