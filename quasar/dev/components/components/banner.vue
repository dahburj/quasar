<template>
  <div class="q-layout-padding bg-grey-3" style="min-height: 100vh">
    <div style="max-width: 500px">
      <q-toggle v-model="dense" label="Dense banners" />

      <q-banner :dense="dense" class="q-my-md">
        <q-icon slot="avatar" name="signal_wifi_off" color="primary" />

        You have lost connection to the internet. This app is offline.

        <q-btn slot="action" flat color="primary" label="Turn ON Wifi" />
        <q-btn slot="action" flat color="primary" label="Dismiss" />
      </q-banner>

      <q-banner :dense="dense" class="q-my-md">
        <q-avatar slot="avatar" icon="signal_wifi_off" color="primary" text-color="white" />

        You have lost connection to the internet. This app is offline.

        <q-btn slot="action" flat color="primary" label="Turn ON Wifi" />
        <q-btn slot="action" flat color="primary" label="Dismiss" />
      </q-banner>

      <q-banner :dense="dense" class="q-my-md">
        <q-avatar slot="avatar" icon="signal_wifi_off" color="primary" text-color="white" />

        You have lost connection to the internet. This app is offline.
      </q-banner>

      <q-banner :dense="dense" class="q-my-md">
        <q-avatar slot="avatar" icon="signal_wifi_off" color="primary" text-color="white" />

        You have lost connection to the internet. This app is offline.

        <q-btn slot="action" flat color="primary" label="Turn ON Wifi" />
      </q-banner>

      <q-banner rounded :dense="dense" class="bg-primary text-white q-my-md">
        <q-avatar slot="avatar" icon="signal_wifi_off" color="white" text-color="primary" />

        You have lost connection to the internet. This app is offline.

        <q-btn slot="action" flat color="white" label="Turn ON Wifi" />
      </q-banner>

      <q-banner inline-actions :dense="dense" class="q-my-md">
        <q-avatar slot="avatar" icon="signal_wifi_off" color="primary" text-color="white" />

        You have lost connection to the internet. This app is offline.

        <q-btn slot="action" flat color="primary" label="Turn ON Wifi" />
      </q-banner>

      <q-banner :dense="dense" class="q-my-md">
        <q-avatar slot="avatar">
          <img src="https://cdn.quasar-framework.org/img/boy-avatar.png">
        </q-avatar>

        You have lost connection to the internet. This app is offline.

        <q-btn slot="action" flat color="primary" label="Turn ON Wifi" />
        <q-btn slot="action" flat color="primary" label="Dismiss" />
      </q-banner>

      <q-banner :dense="dense" class="q-my-md">
        <img slot="avatar" src="https://cdn.quasar-framework.org/img/mountains.jpg" style="width: 100px; height: 64px">

        You have lost connection to the internet. This app is offline.
      </q-banner>

      <q-banner :dense="dense" class="q-my-md">
        You have lost connection to the internet. This app is offline.
      </q-banner>

      <q-banner :dense="dense" class="q-my-md">
        You have lost connection to the internet. This app is offline.

        <q-btn slot="action" flat color="primary" label="Turn ON Wifi" />
      </q-banner>

      <q-banner :dense="dense" class="q-my-md">
        You have lost connection to the internet. This app is offline.

        <q-btn slot="action" flat color="primary" label="Turn ON Wifi" />
        <q-btn slot="action" flat color="primary" label="Dismiss" />
      </q-banner>

      <q-banner inline-actions :dense="dense" class="text-white bg-red q-my-md">
        You have lost connection to the internet. This app is offline.

        <q-btn slot="action" flat color="white" label="Turn ON Wifi" />
      </q-banner>

      <q-banner inline-actions :dense="dense" class="q-my-md">
        You have lost connection to the internet. This app is offline.
        You have lost connection to the internet. This app is offline.

        <q-btn slot="action" flat color="primary" label="Turn ON Wifi" />
        <q-btn slot="action" flat color="primary" label="Dismiss" />
      </q-banner>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      dense: false
    }
  }
}
</script>
