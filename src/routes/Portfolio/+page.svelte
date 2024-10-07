<script>
    import { Gallery } from 'flowbite-svelte';
    
    // Combine all image arrays into a single array
    const images = [
      { alt: 'erbology', src: '/images/2.jpg' },
      { alt: 'shoes', src: '/images/3.png' },
      { alt: 'small bag', src: '/images/4.png' },
      { alt: 'plants', src: '/images/5.jpg' },
      { alt: 'watch', src: '/images/6.png' },
      { alt: 'watch', src: '/images/7.png' },
      { alt: 'watch', src: '/images/8.png' },
      { alt: 'watch', src: '/images/9.png' },
      { alt: 'watch', src: '/images/10.jpg' },
      { alt: 'watch', src: '/images/11.jpg' },
    ];
  </script>
  
  <!-- Use a single Gallery component to display all images -->
  <Gallery class="gap-4 grid-cols-2 md:grid-cols-4" items={images} />
  