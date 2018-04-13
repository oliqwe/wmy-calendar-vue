<template>
  <div id="app">
    <month-calendar></month-calendar>
    <year-calendar></year-calendar>
    <week-calendar></week-calendar>
  </div>
</template>

<script>
import MonthCalendar from './components/month-calendar';
import WeekCalendar from './components/week-calendar';
import YearCalendar from './components/year-calendar';

export default {
  name: 'App',
  components: {
    MonthCalendar,
    WeekCalendar,
    YearCalendar,
  },
};
</script>
