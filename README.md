# BreakBox

BreakBox is a minimalist, single-file web app designed to give you a gentle nudge when you're feeling stuck, bored, or stuck in a rut. It provides a random, simple task to help you take a quick, productive break and inject a little variety into your day. Think of it as your own spontaneity engine.

<table>
  <tr align="center">
    <td align="center">
      <img src="https://github.com/nextfiveinc/breakbox/blob/main/screenshots/Screenshot%20from%202025-08-12%2018-18-10.png" alt="Home screen" width="400">
      <br>
      <em>1-click and break out into something fun. Or healthy. Or useful.</em>
    </td>
 </tr>
</table>


## The Philosophy: Why a Cooldown?

Unlike endless feeds or lists, this tool is designed for **action, not browsing**.

The one-hour cooldown timer is the most important feature. It encourages you to **commit to the suggestion you receive**, rather than endlessly clicking "Something Else" in search of the "perfect" task. The goal is to break the cycle of indecision and get you moving.

## How It Works

1.  **Click "Surprise Me!"** to get a random task.
2.  **Do the Thing!** The suggestions are designed to be quick and easy.
3.  **The Timer Starts.** Once you get a suggestion, a one-hour cooldown begins. You can't get a new prompt until the time is up.
4.  **Add Your Own Ideas.** Use the input box at the bottom to add your own quick tasks to the rotation, making the tool perfectly tailored to you.

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/nextfiveinc/breakbox/blob/main/screenshots/Screenshot%20from%202025-08-12%2018-17-43.png" alt="Home screen" width="200">
      <br>
      <em>Click "Surprise Me" for a suggestion</em>
    </td>
    <td align="center">
      <img src="https://github.com/nextfiveinc/breakbox/blob/main/screenshots/Screenshot%20from%202025-08-12%2018-18-02.png" alt="Suggestion screen" width="200">
      <br>
      <em>Click "Something else" if you want</em> <br>
    </td>
     <td align="center">
      <img src="https://github.com/nextfiveinc/breakbox/blob/main/screenshots/Screenshot%20from%202025-08-12%2018-20-00.png" alt="Add your own task" width="200">
      <br>
      <em>Add your own micro-task like folding laundry</em>
    </td>
    <td align="center">
      <img src="https://github.com/nextfiveinc/breakbox/blob/main/screenshots/Screenshot%20from%202025-08-12%2018-18-10.png" alt="Cooldown screen" width="200">
      <br>
      <em>Act. Don't just browse.</em>
    </td>
 </tr>
</table>

-----

## Features

*   **One-Click Action:** Get a random suggestion from a built-in list of over 30 simple tasks.
*   **Cooldown Timer:** A one-hour timer with a progress bar prevents overuse and encourages action.
*   **"Something Else" Option:** Don't like the first suggestion? You get a couple of chances to ask for another within the first 10 minutes.
*   **Add Custom Tasks:** Personalize the app by adding your own break ideas to the pool of suggestions.
*   **100% Offline & Private:** The app is a single HTML file. All data (your custom tasks, the timer state) is stored locally in your browser. Nothing is ever sent to a server.

## How to Use

1.  **Download:** Save the `breakbox.html` file from this folder.
2.  **Open:** Open the file in any modern web browser.
3.  **Get Unstuck:** Click the button whenever you need a break from your routine.

The app's state is automatically saved in the browser you use, so your cooldown timer and custom tasks will be waiting for you when you return.


## Customization

This app is easy to customize to your own needs directly in the code:

*   **Edit Default Actions:** The list of built-in suggestions is in a simple JavaScript array called `defaultActions` inside the `<script>` tag. You can add, remove, or edit these to your liking.
*   **Adjust Timers:** You can change the `COOLDOWN` and `ELSE_WINDOW` constants at the top of the script to make the timers longer or shorter.

-----

## License

GNU General Public License v3.0 or later. See [COPYING](COPYING) for more details.
