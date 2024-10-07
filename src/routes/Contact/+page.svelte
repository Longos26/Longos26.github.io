<script>
    import { Card, Button, Toggle, List } from 'flowbite-svelte';
    import DescriptionList from 'flowbite-svelte/DescriptionList.svelte';
    let hCard = false;
  </script>
  
  <div class="flex justify-center items-center min-h-screen">
    <div class="space-y-4">
      <Card img="/images/1.jpg" href="/" horizontal size="md" reverse={hCard}>
        <List tag="dl" class="text-gray-900 dark:text-white divide-y divide-gray-200 dark:divide-gray-700">
          <div class="flex flex-col pb-3">
            <DescriptionList tag="dt" class="mb-1">Email address</DescriptionList>
            <DescriptionList tag="dd">romarlongos026@gmail.com</DescriptionList>
          </div>
          <div class="flex flex-col pb-3">
            <DescriptionList tag="dt" class="mb-1">Home address</DescriptionList>
            <DescriptionList tag="dd">BLK 17 Purok 5-D, Sta. Rita. Olongapo City. 2200</DescriptionList>
          </div>
          <div class="flex flex-col pb-3">
            <DescriptionList tag="dt" class="mb-1">Phone number</DescriptionList>
            <DescriptionList tag="dd">0970-203-3292</DescriptionList>
          </div>
          <div class="flex flex-col pb-3">
            <DescriptionList tag="dt" class="mb-1">Github</DescriptionList>
            <DescriptionList tag="dd">Longos26</DescriptionList>
          </div>
          <div class="flex flex-col pb-3">
            <DescriptionList tag="dt" class="mb-1">Facebook</DescriptionList>
            <DescriptionList tag="dd">Romar Longos</DescriptionList>
          </div>
        </List>
      </Card>
      <Toggle bind:checked={hCard} class="italic dark:text-gray-500">Reverse</Toggle>
    </div>
  </div>
  