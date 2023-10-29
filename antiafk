function clickEvery15Seconds() {
  function click() {
    var event = new MouseEvent('click', {
      bubbles: true,
      cancelable: true,
      view: window
    });
    var element = document.elementFromPoint(window.innerWidth / 2, window.innerHeight / 2); 
    element.dispatchEvent(event);

    console.log("click");
  }

  function startClicking() {
    setInterval(function() {
      click();
    }, 15000); 
  }

  startClicking();
}
clickEvery15Seconds();
