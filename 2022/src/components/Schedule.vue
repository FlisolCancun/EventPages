<template>
  <section>
    <Title content="Agenda" />
    <table class="table">
      <tr class="table__tr">
        <td>Horario</td>
        <td>Evento</td>
        <td>Speaker</td>
      </tr>
      <tr v-for="item in schedule" :key="item.event" class="table__tr">
        <td>{{ item.time }}</td>
        <td>{{ item.event }}</td>
        <td>{{ item.speaker }}</td>
      </tr>
    </table>
  </section>
</template>

<script>
import Title from "./Title.vue";

export default {
  components: { Title },
  data() {
    return {
      schedule: [
        {
          time: "12:00 - 12:30",
          event: "Recepción y networking",
          speaker: "",
        },
        {
          time: "12:30 - 13:00",
          event: "Bievenida y anuncios",
          speaker: "",
        },
        {
          time: "13:00 - 14:00",
          event: "Por anunciar",
          speaker: "",
        },
        {
          time: "14:00 - 15:00",
          event: "OpenSource Tools para Estudiantes",
          speaker: "Henry Raygan",
        },
        {
          time: "15:00 - 16:00",
          event: "Por confirmar",
          speaker: "",
        },
        {
          time: "16:00 - 17:00",
          event: "Cracking IT interviews ",
          speaker: "Leandro Tec",
        },
        {
          time: "17:00 - 18:00",
          event: "OpenSource Devops Tools",
          speaker: "Ismael Jimenez",
        },
      ],
    };
  },
};
</script>
