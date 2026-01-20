<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <title>Sie werden zur Studie weitergeleitet.</title>

  <script>
    (function () {
      const random = Math.random();
      const uid = Math.random().toString(36).substring(2, 10);

      if (random < 0.5) {
        // GREEN condition
        window.location.replace(
         " https://docs.google.com/forms/d/e/1FAIpQLScjH4B3QvGZMzkhOfLu2Eb02WMDYnzrZUId0FwkW4zZGOoBdg/viewform?usp=header" + "?condition=green&uid=" + uid
        );
      } else {
        // CONVENTIONAL condition
        window.location.replace(
          "https://docs.google.com/forms/d/e/1FAIpQLSebPm_fyAqfk-z0IOzjLcI2IXSI8ZgsJ7KD26OHpMbTnTvKGw/viewform?usp=sharing&ouid=114484834603649100910" + "?condition=conventional&uid=" + uid
        );
      }
    })();
  </script>
</head>
