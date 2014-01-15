UIView-highlightOnTouch
=======================

dim a view when touched

import "UIView+highlightOnTouch.h"

	#import "UIView+highlightOnTouch.h"

and the set the property highlightOnTouch to YES

	[anyView setHighlightOnTouch:YES];

Please note, if you are using any UIGestureRecognizers on the view, you
have to set the property cancelsTouchesInView to NO on every recognizer

	[gestureRecognizer setCancelsTouchesInView:NO];
