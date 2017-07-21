//

    let tenkan = fast
    let kijun = slow

    let futurePeriod = 10

    let sekkuA = (tekan + kijun)/2 + futurePeriod
    let sekkuB = (tekan + kijun)/2 + (4 * futurePeriod)

    let chikou = lagger


//

if ( current > lastBuy ){
    // sell
}

if ( current < lastSell ){
    // buy
}

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

// if kijun value is +/-2% of the current value
if ( current * 1.05 <= kijun && current * 0.95 >= kijun){
    //
}
