<script>
export default {
  data: () => {
    return {
      copyrightDate: new Date().getFullYear(),
      projectName: "Vue.js Daniel Techer Portfolio",
      author: "Daniel T",
    };
  },
};
</script>

<template>
  <div class="flex justify-center items-center text-center">
    <div
      class="font-general-regular text-lg text-ternary-dark dark:text-ternary-light">
      &copy; {{ copyrightDate }}.
      <a
        href="https://github.com/danitech79"
        target="__blank"
        class="font-general-medium hover:underline hover:text-indigo-600 dark:hover:text-indigo-300 duration-500">
        {{ projectName }}
      </a>
      . Developed by
      <a
        href="https://www.google.fr/search?q=daniel+techer&sca_esv=564173800&sxsrf=AB5stBhuHyamYKnI-9_wRTz4_NG41UseuQ%3A1694361694287&source=hp&ei=Xuj9ZPLUDf2qkdUPj7-CwAE&iflsig=AD69kcEAAAAAZP32boJDhPyrSyFdzkPxUmWQSO3LflLw&ved=0ahUKEwjy-56XtaCBAxV9VaQEHY-fABgQ4dUDCAk&uact=5&oq=daniel+techer&gs_lp=Egdnd3Mtd2l6Ig1kYW5pZWwgdGVjaGVyMgcQIxiKBRgnMgYQABgWGB4yBhAAGBYYHjIIEAAYFhgeGApIlRdQ2wVY0hJwAXgAkAEAmAFOoAHNBqoBAjEzuAEDyAEA-AEBqAIKwgIHECMY6gIYJ8ICBBAjGCfCAg4QLhiABBixAxjHARjRA8ICERAuGIAEGLEDGIMBGMcBGNEDwgILEC4YigUYsQMYgwHCAgsQABiABBixAxiDAcICBRAAGIAEwgINEAAYigUYsQMYgwEYQ8ICBxAAGIoFGEPCAgsQLhiABBixAxiDAcICBxAuGIoFGEPCAggQLhiABBixA8ICBRAuGIAEwgIEEAAYA8ICCxAuGIAEGMcBGK8B&sclient=gws-wiz"
        target="__blank"
        class="font-general-medium text-secondary-dark dark:text-secondary-light uppercase hover:underline hover:text-indigo-600 dark:hover:text-indigo-300 duration-500"
        >{{ author }}</a
      >
    </div>
  </div>
</template>

<style lang="scss" scoped></style>
