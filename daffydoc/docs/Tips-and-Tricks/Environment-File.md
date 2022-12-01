---
hide:
  - toc
---
<script>
  document.title = "Tips and Tricks - Environment File";
</script>
## Your environment file name must follow simple rules:

1. All lower case no spaces
2. Alphanumeric  or - (no special characters)
3. Must end in -env.sh
4. Environment name is the prefix for the file name

    Example:

    /data/daffy/ocp/build.sh **myenv**    =====>   /data/daffy/env/**myenv**-env.sh is the file that daffy would use

5. The **#** at the beginning of the line will mark line as comment only
6. All Names in file must be **UPPER_CASE**
7. All **true/false** values must be lower case
