# CurrentCity
## Installation

To install this package, import 'https://github.com/diasyerlan/CurrentCity' in SPM.

## Usage example

'''swift

import UIKit
import CurrentCity

class ViewController: UIViewController {
    
    override func viewDidLoad() {
        super.viewDidLoad()

        // Initialize the LocationViewController
        let locationVC = LocationViewController()

        // Add it as a child view controller
        addChild(locationVC)
        locationVC.view.frame = view.bounds
        view.addSubview(locationVC.view)
        locationVC.didMove(toParent: self)
    }
}

'''
