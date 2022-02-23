
public class Company extends TaxPayer {
	
	private Integer numberOfEmployees;
	

	public Company(String name, Double anualIncome, Integer numberOfEMployees) {
		super(name, anualIncome);
		this.numberOfEmployees = numberOfEMployees;
	}

	public Integer getNumberOfEMployees() {
		return numberOfEmployees;
	}

	public void setNumberOfEMployees(Integer numberOfEMployees) {
		this.numberOfEmployees = numberOfEMployees;
	}

	@Override
	public Double tax() {
		if(numberOfEmployees > 10) {
			return getAnualIncome() * 0.14;
		} else {
			return getAnualIncome() * 0.16;
		}
	}

}
