# Final Results Section
results_frame = tk.LabelFrame(parent, text="Final Calculations", bg='white', bd=2, relief='solid')
results_frame.pack(fill='x', pady=(10, 0))

# Create results grid
results = [
    ("Weekly Biling before fee", "weekly_billing", "$3,348.00"),
    ("Weekly Pay before Taxes", "weekly_pay", "$2,520.00"),
    ("Diff", "weekly_diff", "$828.00"),
    ("Assignment total Billing", "assignment_billing", "$43,524.00"),
    ("Assignment Total Pay before taxes", "assignment_pay", "$32,760.00"),
    ("Diff", "assignment_diff", "$10,764.00"),
    ("total billing after msp fee", "billing_after_fee", "$3,673.80"),
    ("total pay after taxes", "pay_after_taxes", "$3,180.60"),
    ("Diff", "final_diff", "$2,898.00"),
    ("Total Profit after deduction", "total_profit", "$282.60")
]

for i, (label, key, default) in enumerate(results):
    self.create_cell(results_frame, label, i, 0, width=25, bg_color='#FFE4E1')
    self.calc_vars[key] = self.create_cell(results_frame, default, i, 1, width=15, bg_color='#F0E68C')
