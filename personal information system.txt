<html>
  <head>
    <title>Personal Information System</title>
  </head>
  <body style="background-color:lightblue;">
    <h1>Personal Information System</h1>
    <form action="<?php echo $_SERVER['PHP_SELF']; ?>" method="post">
      <p>
        Please enter a day of the week:
        <input type="text" name="day" />
      </p>
      <input type="submit" value="Submit" />
    </form>
    <?php
      if (isset($_POST['day'])) {
        $day = $_POST['day'];

        switch ($day) {
          case "Monday":
            echo "<p>6am-7am: Morning Walk</p>";
            echo "<p>7am-8am: Breakfast</p>";
             echo "<p>8am-9am: Get ready for college</p>";
             echo "<p>9am-5am:college time</p>";
             echo "<p>5pm-6pm: Tea Break</p>";
             echo "<p>6pm-7pm: study time</p>";
             echo "<p>7pm-8pm: Dinner</p>";
             echo "<p>8pm-9pm: Watching Movies</p>";
             echo "<p>9pm-10pm: Personal Grooming</p>";
             echo "<p>10pm-5am: Sleep</p>";
            break;
          case "Tuesday":
            echo "<p>6am-7am: Morning Walk</p>";
            echo "<p>7am-8am: Breakfast</p>";
             echo "<p>8am-9am: Get ready for college</p>";
             echo "<p>9am-5am:college time</p>";
             echo "<p>5pm-6pm: Tea Break</p>";
             echo "<p>6pm-7pm: study time</p>";
             echo "<p>7pm-8pm: going to temple</p>";
             echo "<p>8pm-9pm:dinner</p>";
             echo "<p>9pm-10pm: Personal Grooming</p>";
             echo "<p>10pm-5am: Sleep</p>";
            break;
          case "Wednesday":
             echo "<p>6am-7am: Morning Walk</p>";
            echo "<p>7am-8am: Breakfast</p>";
             echo "<p>8am-9am: Get ready for college</p>";
             echo "<p>9am-5am:college time</p>";
             echo "<p>5pm-6pm: Tea Break</p>";
             echo "<p>6pm-7pm: study time</p>";
             echo "<p>7pm-8pm: Dinner</p>";
             echo "<p>8pm-9pm: Watching Movies</p>";
             echo "<p>9pm-10pm: Personal Grooming</p>";
             echo "<p>10pm-5am: Sleep</p>";
            break;
          case "Thursday":
             echo "<p>6am-7am: Morning Walk</p>";
            echo "<p>7am-8am: Breakfast</p>";
             echo "<p>8am-9am: Get ready for college</p>";
             echo "<p>9am-5am:college time</p>";
             echo "<p>5pm-6pm: Tea Break</p>";
             echo "<p>6pm-7pm: study time</p>";
             echo "<p>7pm-8pm: Dinner</p>";
             echo "<p>8pm-9pm: Watching Movies</p>";
             echo "<p>9pm-10pm: Personal Grooming</p>";
             echo "<p>10pm-5am: Sleep</p>";
            break;
          case "Friday":
            echo "<p>6am-7am: Morning Walk</p>";
            echo "<p>7am-8am: Breakfast</p>";
             echo "<p>8am-9am: Get ready for college</p>";
             echo "<p>9am-5am:college time</p>";
             echo "<p>5pm-6pm: Tea Break</p>";
             echo "<p>6pm-7pm: study time</p>";
             echo "<p>7pm-8pm: going to temple</p>";
             echo "<p>8pm-9pm:dinner</p>";
             echo "<p>9pm-10pm: Personal Grooming</p>";
             echo "<p>10pm-5am: Sleep</p>";
            break;
          case "Saturday":
            echo "<p>6am-7am: Morning Walk</p>";
            echo "<p>7am-8am: Breakfast</p>";
             echo "<p>8am-9am: Get ready for college</p>";
             echo "<p>9am-5am:college time</p>";
             echo "<p>5pm-6pm: Tea Break</p>";
             echo "<p>6pm-7pm: study time</p>";
             echo "<p>7pm-8pm: going to temple</p>";
             echo "<p>8pm-9pm:dinner</p>";
             echo "<p>9pm-10pm: Personal Grooming</p>";
             echo "<p>10pm-5am: Sleep</p>";
            break;
          case "Sunday":
             echo "<p>8am-9am: breakfast</p>";
             echo "<p>10am-5pm: Personal works</p>";
             echo "<p>5pm-7pm:playing carom</p>";
             echo "<p>7pm-8pm:dinner</p>";
             echo "<p>8pm-9pm:watching tv</p>";
             echo "<p>9pm-6am:sleep</p>";
            break;
          default:
            echo "<p>Invalid day.</p>";
        }
      }
    ?>
  </body>
</html>