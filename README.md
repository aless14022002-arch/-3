gsap.to([cordWrapper, ribbon], {
    opacity: 0,
    duration: 1,
    onComplete: () => {
      cordWrapper.style.display = "none"
      ribbon.style.display = "none"
    }
  });
