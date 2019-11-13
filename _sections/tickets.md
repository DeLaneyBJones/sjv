---
layout: form
order: 6
header: Order Form
slides: [
            ["Member Info",
                ["e-mail", "email"],
                ["first name", "text"],
                ["last name", "text"],
                ["address", "text"],
                ["city", "text"],
                ["state", "text"],
                ["zip", "number"],
                ["phone", "tel"]
            ],
            ["Order Info",
                ["order type", "select", [
                                            "select order type",
                                            "member package",
                                            "donor type",
                                            "single tickets"
                                        ]
                ],
                ["number of tickets","number"]
            ],
            ["Payment Method",
                ["bill me","radio"],
                ["credit card","radio", 
                                        ["Credit Card Info",
                                            ["card type", "select", [
                                                                        "Visa",
                                                                        "Master Card",
                                                                        "Discover"
                                                                    ]
                                            ],
                                            ["card number", "number"],
                                            ["exp. date", "date"]
                                        ],
                ]
            ]
        ]
---