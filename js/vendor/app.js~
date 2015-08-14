/* default dom id (particles-js) */
//particlesJS();

/* config dom id */
//particlesJS('dom-id');

/* config dom id (optional) + config particles params */
  width = $(document).width();
    if (width>768){
        num_nb = Math.round(Math.sqrt(width * 15));
    }else{
        num_nb = Math.round(Math.sqrt(width * 3));
    }
    console.log(num_nb)

     particlesJS('particles-js', {
        particles: {
            color: '#fff',
            shape: 'circle', // "circle", "edge" or "triangle"
            opacity: .6,
            size: 3,
            size_random: true,
            nb: num_nb,
            line_linked: {
                enable_auto: true,
                distance: 110,
                color: '#fff',
                opacity: 1,
                width: 1,
                condensed_mode: {
                    enable: false,
                    rotateX: 600,
                    rotateY: 600
                }
            },
            anim: {
                enable: true,
                speed: 3
            }
        },
        interactivity: {
            enable: true,
            mouse: {
                distance: 250
            },
            detect_on: 'canvas', // "canvas" or "window"
            mode: 'grab',
            line_linked: {
                opacity: .5
            },
            events: {
                onclick: {
                    enable: false,
                    mode: 'push', // "push" or "remove" (particles)
                    nb: 4
                }
            }
        },
        /* Retina Display Support */
        retina_detect: true
    });

$(window).resize(function(){
    $('#absolute').css({
        position:'absolute',
        left: ($(window).width() - $('#absolute').outerWidth())/2,
        top: ($(window).height() - $('#absolute').outerHeight())/2
    });

});

// To initially run the function:
$(window).resize();