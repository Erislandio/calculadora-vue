<template>
  <div class="calculator">
    <Display/>
    <Button/>
    <Button/>
    <Button/>
    <Button/>
    <Button/>
    <Button/>
  </div>
</template>

<script>
import Display from "../display";
import Button from "../button";

export default {
  components: {
    Button,
    Display
  }
};
</script>

<style>
    .calculator{
        height: 320px;
        width: 235px;
        border-radius: 5px;
        overflow: hidden;

        display: grid;
        grid-template: repeat(4, 25%);
        grid-template-rows: 1fr 48px 48px 48px 48px 48px;

    }
</style>
