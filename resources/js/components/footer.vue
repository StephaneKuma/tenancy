<template>
  <footer class="footer">
    <BContainer fluid>
      <BRow>
        <BCol sm="6">{{ new Date().getFullYear() }} {{ "-" }} {{ new Date().getFullYear() + 1 }} © Tenancy.</BCol>
        <BCol sm="6">
          <div class="text-sm-end d-none d-sm-block">Design & Develop by Stéphane Kuma</div>
        </BCol>
      </BRow>
    </BContainer>
  </footer>
</template>
