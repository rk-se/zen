<template>
  <div class="highlights-item col-md-4 col-sm-6 col-xs-12 border-top">
    <div>
    <div class="card-heading pt-5">Wind Status</div>
    <div class="row pt-4 mt-4">
      <div class="col-sm-6 col-md-6 mt-2 text-center align-middle">
        <p class="card-sub-heading mt-3">Wind Direction</p>
        <p class="mt-4">
          <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" viewBox="0 0 24 24">
            <g fill="none" fill-rule="evenodd">
              <rect width="24" height="24"/>
              <path stroke="#ef473a" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7.59,0.59 C8.22943344,-0.0532334709 9.22166587,-0.185649514 10.0074001,0.267391566 C10.7931342,0.720432645 11.1756399,1.64549947 10.9393079,2.52115443 C10.7029759,3.39680939 9.90697846,4.00380802 9,4 L0,4.00001782 M10.59,15.41 C11.2294334,16.0532335 12.2216659,16.1856495 13.0074001,15.7326084 C13.7931342,15.2795674 14.1756399,14.3545005 13.9393079,13.4788456 C13.7029759,12.6031906 12.9069785,11.996192 12,12 L0,11.9999822 M15.73,3.73 C16.5304438,2.93158082 17.7671032,2.76972383 18.7460635,3.33525029 C19.7250238,3.90077676 20.2026103,5.05292057 19.9108396,6.14519034 C19.6190688,7.23746012 18.6305659,7.99797722 17.5,8 L0,8" transform="translate(2 4)"/>
            </g>
          </svg>
        </p>
        <p class="card-value mt-4">{{ highlights.windStatus.derivedWindDirection }}</p>
      </div>
      <div class="col-sm-6 col-md-6 mt-2">
        <p class="card-sub-heading mt-3">Wind Speed</p>
        <p class="mt-4">
          <svg width="40" height="40" viewBox="0 0 28 28" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
            <!-- Generator: sketchtool 52.1 (67048) - http://www.bohemiancoding.com/sketch -->
            <title>56A71BAE-15B9-49DC-A730-B69CF475ABFB</title>
            <desc>Created with sketchtool.</desc>
            <g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                <g id="Weather-Dashboard" transform="translate(-945.000000, -519.000000)">
                    <g id="Group-17" transform="translate(760.000000, 479.000000)">
                        <g id="Group-21-Copy" transform="translate(162.000000, 0.000000)">
                            <g id="Icon-/-windspeed" transform="translate(22.000000, 39.000000)">
                                <rect id="Rectangle" fill-rule="nonzero" x="0" y="0" width="30" height="30"></rect>
                                <g id="if_performance-clock-speed_353431" transform="translate(1.250000, 1.250000)" fill="#ef473a">
                                    <path d="M11.8308173,13.9543627 C11.8308173,13.1541667 12.2676442,12.465049 12.9059615,12.0978431 L12.8996154,12.0913725 L19.62125,7.88872549 L15.7924038,14.9319608 L15.7865865,14.9265686 C15.4386058,15.6162255 14.7415865,16.0928922 13.9282212,16.0928922 C12.7705769,16.0928922 11.8308173,15.1352451 11.8308173,13.9543627 Z M22.378125,3.76426471 L20.0453846,6.0570098 C18.4810577,4.72083333 16.9230769,3.86455882 14.2788462,3.69308824 L14.2788462,0.443235294 C17.4519231,0.626029412 20.2288942,1.84897059 22.378125,3.76426471 Z M23.8752885,12.9411765 C23.6743269,10.7843137 22.7816346,8.73691176 21.4246154,7.15161765 L23.6769712,4.86911765 C25.6040865,7.04754902 26.8452885,9.70588235 27.0589423,12.9411765 L23.8752885,12.9411765 Z M23.8900962,14.5588235 L27.0795673,14.5588235 C26.7405769,21.5686275 20.8397115,27.4627941 13.73625,27.4627941 C6.41543269,27.4627941 0.376009615,21.4187255 0.376009615,13.9543627 C0.376009615,6.76176471 5.81730769,0.863823529 12.6923077,0.44377451 L12.6923077,3.69362745 C7.93269231,4.10882353 3.54908654,8.53308824 3.54908654,13.9403431 C3.54908654,19.6204412 8.24841346,24.2275 13.8198077,24.2275 C19.1717308,24.2275 23.5532212,19.9509804 23.8900962,14.5588235 Z" id="Combined-Shape"></path>
                                </g>
                            </g>
                        </g>
                    </g>
                </g>
            </g>
          </svg>
        </p>
        <p class="card-value mt-4">{{ highlights.windStatus.windSpeed }} km/h</p>
      </div>
    </div>
    </div>
  </div>
</template>

<script>
export default {
  props: ["highlights"],
};
</script>