//

    let tenkan = fast
    let kijun = slow

    let futurePeriod = 10

    let sekkuA = (tekan + kijun)/2 + futurePeriod
    let sekkuB = (tekan + kijun)/2 + (4 * futurePeriod)

    let chikou = lagger


//


if (chikou > tekan &&
    chikou > kijun &&
    chikou > sekkuA &&
    chikou > sekkuB) {
        // bull
    }

if ( tenkan > kijun ){
    // bull
}

if ( tenkan < kijun ){
    // bear
}

if ( current * 1.02 <= kijun && current * 0.8 >= kijun){
    
}
