# image_glitcher


in the doRules() function there something like this:


    if (neighbours.n && neighbours.n.g > px.g) {
                nextGen[px.pos.y][px.pos.x] = { ...px, r: px.r * 1.01 }
                changed = true
            }
            
            
            
            
            these are the rules to change the pixel data
