<template>
  <div class="row items-stretch">
    <div class="col-6 q-pa-md">
      <q-card class="full-height q-pa-md">
        <q-form class="q-gutter-md">
          <q-input filled label="Username *" />

          <q-input filled type="password" label="Password *" />

          <div>
            <q-btn label="Submit" type="submit" color="primary" />
          </div>
        </q-form>
      </q-card>
    </div>

    <div class="col-6 q-pa-md">
      <q-card class="full-height">
        <q-img src="https://picsum.photos/500/300" class="full-height" />
      </q-card>
    </div>
  </div>
</template>
