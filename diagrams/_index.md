
<style>
text-wbg {
    background-color: #5beeb7a6;
    padding: 2px 5px;
    border-radius: 4px;
    font-weight: 600;
    margin-bottom: 4rem !important;
}
ul li {
    margin-bottom: .5rem;
}
mid-width {
    display: inline-block;
    max-width: 60rem;
}
svg#journey {
    max-height: 760px !important;
    max-width: 1040px !important;
    margin-left: 0;
  }
  g[id^="frame-link"]:hover text {
    fill: rgb(255, 255, 255);
    transform: matrix(1, 0, 0, 1, 0, 0);
  }
g#step1:hover rect#step-rect-1,
    g#step2:hover rect#step-rect-2,
    g#step3:hover rect#step-rect-3,
    g#step4:hover rect#step-rect-4 {
        fill: url(#rainbowGradient);
        transition: fill 1s ease-in-out;
    }

g[id^="frame-link"]:hover rect {
  fill: black !important;
  fill-opacity: 80%;
  rx: 8;
  ry: 8;
}
g[id^="frame-link"]:hover {
  cursor: pointer;
}
</style>

This section provides a step-by-step guide on how to develop and release apps.

{{% svg "/static/images/content/dev-journey/interactive-diagram-example.svg" %}}