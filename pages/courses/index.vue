<template>
  <HeroCourses_Courses></HeroCourses_Courses>
  <TabCourses_Courses></TabCourses_Courses>
  <Courses_Courses></Courses_Courses>
  <TabCourses_Courses_Windows></TabCourses_Courses_Windows>
</template>
<script>
import HeroCourses_Courses from "@/components/courses/HeroCourses_Courses.vue";
import Courses_Courses from "@/components/courses/Courses_Courses.vue";
import TabCourses_Courses from "@/components/courses/TabCourses_Courses.vue";
import TabCourses_Courses_Windows from "~/components/courses/TabCourses_Courses_Windows.vue";

export default {
  components: {
    TabCourses_Courses_Windows,
    HeroCourses_Courses,
    Courses_Courses,
    TabCourses_Courses,
  },
};
</script>
