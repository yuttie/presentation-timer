# Presentation Timer

## Usage
- Configuration via a query string in URL:
    - `duration`: Presentation time in minutes, e.g. `duration=20`
    - `bell`: Ring the bell at specified times, e.g. `bell=15,18,20` to ring at 15, 18 and 20 minutes
        - You can specify more than three, but only three kinds of bell sound are available
    - `rev`: Reverse mode in which remaining time is shown, e.g. `rev=true` (default) or `rev=false`
        - This does NOT change the interpretation of `bell` parameter values
- Just click/tap the page to start

## Examples

- Just elapsed time: https://yuttie.info/presentation-timer/
- 5-min presentation, bells at 3, 4, and 5 mins: https://yuttie.info/presentation-timer/?duration=5&bell=3,4,5

## Credits

The bell sounds included in this repository are modified versions of the following work:
- ["Bell, Counter, A.wav" by InspectorJ (www.jshaw.co.uk) of Freesound.org](https://freesound.org/people/InspectorJ/sounds/415510/)
